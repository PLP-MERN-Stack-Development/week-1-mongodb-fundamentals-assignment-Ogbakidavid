# MongoDB Fundamentals Assignment

## How to Run the Script

1. **Ensure MongoDB is installed and running** on your machine.  
   You can download MongoDB from [mongodb.com](https://www.mongodb.com/try/download/community).

2. **Open the MongoDB shell** (`mongosh`) or connect to your MongoDB instance.

3. **Switch to your database** (replace `your_database` with your actual database name):
   ```
   use your_database
   ```

4. **Copy and paste the queries** from `queries.js` into the MongoDB shell to execute them.

   - Each command in `queries.js` is a standalone MongoDB query or aggregation.
   - You can run them one by one as needed.

## Notes

- Make sure your `books` collection exists and contains documents with the appropriate fields (e.g., `title`, `author`, `published_year`, `genre`, `price`, `in_stock`).
- The script is intended for use in the MongoDB shell, not as a standalone Node.js script.

