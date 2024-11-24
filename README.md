
# WhatsDown Messaging Web Application  

**A Web Programming Project**  

An amateur-inspired messaging application akin to WhatsApp, with features such as user search, contact management, and customizable chat settings. Users can:  
- Add or remove contacts.  
- Send visible/hidden text messages or images (similar to Discord).  
- Customize chat wallpapers or set wallpaper colors.  
- Toggle between light and dark themes.  

All data is securely stored in a MySQL database.

---

## 🛠️ Technical Details  

- **Frontend**:  
  - Built with **vanilla JavaScript**, **HTML**, **CSS**, and **Bootstrap**.  
  - JavaScript is modularized into two files: one for the login page and another for the main app functionality.  

- **Backend**:  
  - Powered by **PHP**.  
  - Each server request corresponds to a specific PHP script, organized within a dedicated `php_scripts` folder.  

- **Hosting**:  
  - The web application is hosted locally using **XAMPP**.  
  - Uses an **Apache server** to execute PHP scripts.  
  - MySQL server is employed for managing the application's database.

---

## 🚀 Setting It Up  

### 1. Installing XAMPP  
Download the appropriate version of XAMPP for your operating system from the [official website](https://www.apachefriends.org/index.html).  

### 2. Cloning the Repository  
Navigate to the `htdocs` directory of your XAMPP installation:  
```bash
cd xampp/htdocs
```  

Clone the repository:  
```bash
git clone https://github.com/mmswflow-upb/WhatsDown-IWP-Project.git
```

### 3. Running the Application  
- Open the XAMPP application.  
- Start the **Apache** and **MySQL** services by clicking the "Start" buttons next to them.  
- The application should now be accessible through your web browser.  

### 4. Setting Up the Database  

#### Accessing the Database Admin Page  
- Click the "Admin" button next to "MySQL" in the XAMPP interface.  
- You will be redirected to the **PHPMyAdmin** page.  

#### Creating the Database  
- In PHPMyAdmin, click the **"New"** button on the left panel.  
- Create a new database and name it `whatsdowndb`.  

#### Creating the Users Table  
- Select the `whatsdowndb` database from the left panel.  
- Go to the **"SQL"** tab.  
- Copy the commands from the provided SQL script and paste them into the text box.  
- Click **"Go"** to execute the commands and create the necessary tables.  

### 5. Accessing the Application  
In your browser, navigate to:  
```  
http://localhost/WhatsDown-IWP-Project  
```

---

## 📚 Notes  

- Ensure XAMPP is running whenever you access the application locally.  
- Modify the SQL script if you wish to customize the database structure.  
- Use `php_scripts` for adding new functionality to the backend.  
