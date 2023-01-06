# simple-portfolio-project-using-tailwindcss
## Tailwind Elements
Tailwind Elements is a plugin that extends the functionality of the library with many interactive components.

In some dynamic components (like dropdowns or themechange) I add custom JavaScript.

It is Dynamic website with five sections.
+ Introduction
+ About me
+ Services
+ Project
+ Contact

## Project Setup
1. Install any of the code editor(Here i am using Visual Studio Code).
2. Using Terminal:
    + ***Install Tailwind CSS:***
         Install tailwindcss via npm, and create your tailwind.config.js file.
          
              npm install -D tailwindcss
              npx tailwindcss init
    + ***Configure your template paths:***
         Add the paths to all of your template files in your tailwind.config.js file.
             
              module.exports = {
              content: ["./src/**/*.{html,js}"],
              theme: {
              extend: {},
              },
              plugins: [],
              }
    + ***Add the Tailwind directives to your CSS:***
    
            @tailwind base;
            @tailwind components;
            @tailwind utilities;
    + ***Start the Tailwind CLI build process:***
        
            npx tailwindcss -i ./input.css -o ./css/output.css --watch
    + ***Start using Tailwind in your HTML***
         

## Demo link
https://drive.google.com/file/d/1-v2nUBvuMDpGkgi4QVmW7O_OKjUtAceE/view?usp=share_link
