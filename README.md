# Simple Calendar HTTP Server in Node.js

This project showcases a straightforward HTTP server implemented in ``Node.js``, serving as the backend for calendar-related queries. The server functionality includes the ability to manipulate dates by adding days and weeks to the current date or subtracting days from a specified date. The project is containerized using ``Docker`` to streamline deployment and manage dependencies effectively.

## Getting Started

### Prerequisites

Make sure you have Node.js installed on your machine. You can download it from [Node.js official website](https://nodejs.org/).

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/your-repo.git

2. Navigate to the project directory:
   ```bash
   cd your-repo
   ```
3. Install dependencies:
    ```bash
    npm install
    ```

### Usage

1. Start the server:

   ```bash
   node index.js
   ```
#### The server will be running at http://localhost:3000. 

###Examples

1. Add 6 days to today:
  ```bash
   http://localhost:3000/?action=addDays&days=6
  ```

2. Add 6 weeks to today:
  ```bash
   http://localhost:3000/?action=addWeeks&weeks=6
  ```
3. Subtract 187 days from 12-jan-2019:
   ```bash
      http://localhost:3000/?action=subDays&days=187
   ```

### Dependencies

1. date-fns: Used for date manipulation.

### License
 This project is licensed under the MIT License.
   
