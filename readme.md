# Cricketangon - Phase One

**Cricketangon** is a cricket-focused platform designed to provide users with a dynamic experience. This phase includes essential features for user interaction and content management, tailored for cricket enthusiasts.

## Features

### User Features:
- **User Registration & Login**: Secure user authentication system.
- **Profile Management**: Users can manage their profiles.

### Admin Features:
- **Content Management**: Admins can write, edit, and delete blogs and articles related to cricket.
- **Player & Stats Management**: Admins can add, update, and manage player information and statistics.
- **Photo Gallery**: Upload and manage cricket-related images.
- **Advanced Filtering and Search**: Efficient query options for easy navigation and content discovery.

### Additional Functionalities:
- Full **CRUD Operations** for all entities.
- Advanced **filtering**, **sorting**, and **search capabilities** for optimized content management.

## Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/rafin8990/Cricketangon-Backend.git
```
2. **Go inside Project**:
 ```bash
  cd Cricketangon-backend
```
3. ** Install Dependencies"
   ```bash
   npm install
   ```
4. ** Setup .env ** </br>
make a .env file and add this:
```bash
NODE_ENV="development"
PORT=3000;
BCRYPT_SAULT_ROUND=12
DEFAULT_USER_PASSWORD="user1234"
JWT_SECRET="secret"
JWT_EXPIRES_IN='1d'
JWT_REFRESH_SECRET="very very secret"
JWT_REFRESH_EXPIRES_IN='365d'
DB_HOST=localhost
DB_PORT=3306
DB_USERNAME="root"
DB_PASSWORD=""
DB_NAME="cricketangon"
EMAIL_USER=""
EMAIL_PASSWORD=""
EMAIL_FROM=""
```
