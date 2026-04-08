# Willy Shop

## Project Structure

### Backend
- **/backend**
    - **/src**
        - **/controllers**  # Functionality to handle incoming requests
        - **/models**       # Database models
        - **/routes**       # Define API routes
        - **/middlewares**   # Middleware for authentication, etc.
        - **/config**       # Configuration files (e.g., database connection)
    - **/tests**             # Test cases for the backend
    - `server.js`          # Main server file
    - `package.json`       # Node.js dependencies for backend

### Frontend
- **/frontend**
    - **/src**
        - **/components**   # React components
        - **/containers**    # Container components for state management
        - **/assets**        # Images, fonts, and other assets
        - **/styles**        # Styles and CSS files
    - **/public**           # Public files (index.html, etc.)
    - `package.json`       # Node.js dependencies for frontend

### Configurations
- `.gitignore`           # Ignore node_modules, logs, etc.
- `README.md`            # Project documentation
- `docker-compose.yml`   # Docker configuration file for services
- `Dockerfile`           # Specify image for backend
- `migration.sql`        # SQL scripts for database migrations