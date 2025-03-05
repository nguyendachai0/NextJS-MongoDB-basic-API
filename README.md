# NestJS Products API

## Description
A comprehensive CRUD (Create, Read, Update, Delete) API for managing products built with NestJS and MongoDB. This project demonstrates a robust backend application with RESTful endpoints for product management.

## Prerequisites
- Node.js (v16 or later)
- npm (v8 or later)
- MongoDB (v5 or later)

## Installation

### 1. Clone the Repository
```bash
git clone https://github.com/nguyendachai0/NextJS-MongoDB-basic-API.git
cd NextJS-MongoDB-basic-API
```

### 2. Install Dependencies
```bash
npm install
```

### 3. Set Up Environment
Create a `.env` file in the project root with the following content:
```env
MONGODB_URI=mongodb://localhost:27017/products-db
PORT=3000
```

### 4. Running the Application
```bash
# Development mode with hot reload
npm run start:dev  

# Production mode
npm run start:prod  
```

## API Endpoints

### Products Endpoints
- `GET /products`: Retrieve all products
- `POST /products`: Create a new product
- `GET /products/:id`: Retrieve a specific product by ID
- `PUT /products/:id`: Update an existing product
- `DELETE /products/:id`: Delete a product

### Example Request Body for Creating/Updating a Product
```json
{
  "name": "Wireless Headphones",
  "description": "High-quality noise-cancelling headphones",
  "price": 199.99,
  "stock": 50
}
```

## Testing
```bash
# Unit tests
npm run test  

# End-to-end tests
npm run test:e2e  
```

## Technologies Used
- NestJS
- MongoDB
- Mongoose
- TypeScript

## Project Structure
```
src/
├── main.ts
├── app.module.ts
└── products/
    ├── dto/
    ├── schemas/
    ├── products.controller.ts
    ├── products.service.ts
    └── products.module.ts
```

## Contributing
1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License
Distributed under the MIT License. See `LICENSE` for more information.

## Contact
**Nguyen Dac Hai**  
Email: [haindfullstack@gmail.com](mailto:haindfullstack@gmail.com)  
Project Link: [GitHub Repository](https://github.com/nguyendachai0/NextJS-MongoDB-basic-API)
