
<h1 align="center">Project Setup and Installation</h1>


<h2>Installation and Setup</h2>

<h3>1. Install Dependencies</h3>
In the root directory, run:

```
npm i
```


<h3>2. Configure Database</h3>
Update the database URL in the `.env` file:
```
DATABASE_URL=your_database_url_here
```

<h3>3. Running the Application</h3>

<h4>Backend</h4>
1. Navigate to the backend folder


2. Run the Python server:
```
python main.py
```

<h4>Frontend</h4>
1. Open a new terminal

2. Navigate to the frontend folder
   
3. Start the development server:
```
npm run dev
```

<h2>Usage Notes</h2>

<h3>Lead Management</h3>
- To schedule a meeting for a lead in the leads page, ensure the lead stage is set to <bold>"Action Taken"</bold>

<h3>API Documentation</h3>
- Once the backend is running, you can view all available API routes at:

  ```
  http://localhost:8000/docs
  ```

