# CI/CD Pipeline

### Pipeline workflow

1. Push code to remote repository main branch.
2. CircleCI setup pipeline orbs.
3. Build job starts
4. Install and setup environment.
5. Commands:
    - Install frontend dependencies.
    - Install API dependencies.
    - Build frontend.
    - Build API.
    - Test frontend.
    - Deploy frontend.
    - Deploy API.

### IF all goes well, the workflow succeeds.
