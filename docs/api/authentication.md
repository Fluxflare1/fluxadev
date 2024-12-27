# Authentication API

## Endpoints
1. **POST /api/auth/login**
   - Description: Authenticates a user.
   - Payload:
     ```json
     {
       "username": "string",
       "password": "string"
     }
     ```

2. **POST /api/auth/register**
   - Description: Registers a new user.
   - Payload:
     ```json
     {
       "username": "string",
       "email": "string",
       "password": "string"
     }
     ```
