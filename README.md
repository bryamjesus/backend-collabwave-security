# Security
## Architecture
```
src/main/java/com/collabwave/security
├── controller
│   └── AuthController.java
├── dto
│   └── Login
│   │   ├── LoginRequest.java
│   └── └── LoginResponse.java
├── model
│   └── User.java
├── repository
│   └── UserRepository.java
├── security
│   ├── JwtProvider.java
│   └── SecurityConfig.java
├── service
│   └── AuthService.java
└── AuthServiceApplication.java
```