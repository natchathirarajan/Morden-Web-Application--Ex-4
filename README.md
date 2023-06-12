# Exp-4 Create a Web-Layout using GridBOX.
## Aim:
To write HTML & CSS code to create Web-Layout using GridBOX.
## Algorithm:
### Step 1:
Create a html code for the Web-Layout.
### Step 2:
Make style for the Web Layout using style tag.
### Step 3:
Include Style in the html using class and id Selector.
### Step 4:
Verify the output by running the Web-Layout in any web browser. 
## Program:
### HTML & CSS:
```html
<!DOCTYPE html>
<html>
<head>
  <style>
    body {
      margin: 0;
      padding: 0;
      font-family: Arial, sans-serif;
    }

    .container {
      display: grid;
      grid-template-columns: 1fr;
      grid-template-rows: auto 1fr auto;
      min-height: 100vh;
    }

    .header {
      grid-column: 1;
      background-color: #41b3a3;
      width:1500px;
      padding: 20px;
      text-align: center;
    }

    .sidebar {
      grid-column: 1;
      background-color: #85DCB8;
      padding: 20px;
      height: 500px;
    }

    .main-content {
      grid-column: 2;
      background-color: #ffffff;
      padding: 20px;
    }

    .footer {
      grid-column: 1;
      width: 1500px;
      background-color: #41b3a3;
      padding: 20px;
      text-align: center;
    }

    @media (min-width: 768px) {
      .container {
        grid-template-columns: 300px 1fr;
        grid-template-rows: auto 1fr auto;
      }
    }
  </style>
</head>
<body>
  <div class="container">
    <div class="header">
      <h1>VM Creators</h1>
    </div>
    <div class="sidebar">
        <h2>Our Works</h2>
        <ul>
          <li>React Webpage</li>
          <li>SpringBoot Webpage</li>
          <li>Angular Webpage</li>
        </ul>
    </div>
    <div class="main-content">
      <h1>Welcome to My Website</h1>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Curabitur tristique lectus id neque mollis semper. Sed ac tellus sed ex vulputate ultrices.</p>
    </div>
    <div class="footer">
      <p>&copy; 2023 VM Creators. All rights reserved.</p>
    </div>
  </div>
</body>
</html>
```
## Output:
![image](https://github.com/Karthikeyan21001828/MERN_EX04/assets/93427303/7b8ff3e2-f89d-45c4-844d-03713f0a160d)
## Result:
Thus the HTML & CSS code to create Web-Layout using GridBOX has been created and output has been verified.
