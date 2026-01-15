## Test Scenarios – Library API

### Add Book API
- Validate successful book creation (200 OK)
- Validate response message
- Validate generated Book ID logic (isbn + aisle)
- Handle duplicate book creation gracefully
- Validate response headers and response time

### Get Book API
- Validate correct book retrieval by ID
- Validate JSON schema
- Validate author and book name consistency

### Delete Book API
- Validate successful deletion
- Validate cleanup after duplicate entry detection
