# Rule Engine

A React application that allows users to create, combine, and evaluate rules. The rules are represented as Abstract Syntax Trees (AST) and can be visualized using a tree structure.

---

## 🚀 Features

### ✨ Rule Management

- **Create Rule**:  
  - Input rules in the format `field operator value` (e.g., `age > 30`), which are validated and converted to an AST.
  - The AST visualization appears on the frontend (initially in the left corner, draggable to the center).

### 🔗 Rule Combination

- **Combine Rules**:  
  - Merge multiple rules using logical operators (`AND`, `OR`) to form a complex rule represented as a single AST.
  - The combined AST visualization is shown (drag to the center if needed).

### ✅ Rule Evaluation

- **Evaluate Rule**:  
  - Check if the JSON data satisfies the conditions defined by the combined AST.
  - Returns `True` or `False` based on the evaluation.

### 🌳 AST Visualization

- **Visualize AST**:  
  - View tree diagrams of individual and combined rules using `react-d3-tree`.
  - Drag-and-drop functionality allows for easy adjustment of the tree position.
---

Here’s a beautified version of the "Prerequisites" and "Getting Started" sections for your README:

---

## 🛠️ Prerequisites

- **Node.js** (v14 or later)
- **npm** (v6 or later)

## 🚀 Getting Started

Here’s a beautified version of your content for the README, with proper formatting and organization:

---

### 📥 Clone the Repository

```bash
git clone https://github.com/amantripathigithub/Application-1-Rule-Engine-with-AST.git
cd Application-1-Rule-Engine-with-AST
```

### Backend Setup

1. **Navigate to the backend directory:**
   ```bash
   cd backend
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Start the backend server:**
   ```bash
   node index.js
   ```
   The backend server will run on [http://localhost:5000](http://localhost:5000).

---

### Frontend Setup

1. **Navigate to the frontend directory:**
   ```bash
   cd frontend
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Start the frontend development server:**
   ```bash
   npm start
   ```
   The frontend server will run on [http://localhost:3000](http://localhost:3000).

---

### Usage

1. **Open your web browser and navigate to [http://localhost:3000](http://localhost:3000).**

2. **Create Rule:**
   - Enter a rule in the input field and click "Create Rule". The rule should be in the format `field operator value` (e.g., `age > 30`).

3. **Combine Rules:**
   - After creating at least two rules, click "Combine Rules" to combine them into a single AST.

4. **Evaluate Rule:**
   - Enter JSON data in the textarea (e.g., `{"age": 32, "department": "Sales"}`) and click "Evaluate Rule". The result (true/false) will be displayed based on whether the data satisfies the combined rule.

5. **Visualize AST:**
   - The AST for individual rules and the combined AST will be displayed as tree structures.

---

### Example

1. **Create the following rules:**
   - `age > 30`
   - `department = Sales`
   - `age < 25`
   - `department = Marketing`

2. **Combine the rules.**

3. **Enter the following JSON data for evaluation:**
   ```json
   {
     "age": 32,
     "department": "Sales"
   }
   ```

   The evaluation result should be **true** if the combined AST is satisfied by the provided data.

--- 



```
