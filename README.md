# Archetype for simple WEB project

Archetype to create simple WEB project using JSF, JPA, CDI, security etc.

This archetype helps you to create boilerplate project with all configuration and set of pages for user registration, login and resetting password.

For registration and password resetting this app will send emails with confirmation code.

# What you will have out of the box

## Registration screen

![register - step1](img/register1.png)

After entering data email will be sent to confirm email address:

![register - step2](img/register2.png)

## Login screen

![sign in](img/signin.png)

## Resetting password

If users lost their password it will be possible to change it. Confirmation code will be sent by email.

![reset - step1](img/reset1.png)

![register - step2](img/reset2.png)

# How to start

## From Intellij IDEA

### Step 1

1. Start creating new project `File -> New -> Project`

2. In the New Project dialog from the left sidebar select Maven.

3. Select checkbox `Create from archetype`

4. Press button `Add Archetype...`

5. Enter following data and click `OK`:
   
   Group Id:    `guru.bug.javacourses`
   
   Artifact Id: `webproject`
   
   Version:     `2.0.0`
   
   Repository:  *leave empty*
   
![step 1](img/step01.png)

### Step 2

1. Find `guru.bug.javacourses:webproject` in the list and expand it. 

2. There is entry `webproject:2.0.0` - select it. 

3. Press `Next`

![step 2](img/step02.png)

### Step 3

1. Fill the form and press `Next`:
   
   Group Id: your project's group id. This is also base package for the project. For example `lv.tsi.javacourses`

   Artifact Id: name of your project. Please don't use dashes, dots, spaces - only latin letters and numbers. For example `myCatalog`. 
   This will be used not only maven artifact id, but as datasource, database and context root.
   
   Version: `1.0-SNAPSHOT` by default, but any version number you like.
 
![step 3](img/step03.png)

### Step 4
   
Next form is informational, you may skip it pressing `Next`

![step 4](img/step04.png)

### Step 5

1. Ensure right directory is selected for you project to be created. 

2. And press `Finish`

![step 5](img/step05.png)

### Step 6

1. Examine created project

2. Follow instructions in `README.md` to continue

![step 6](img/step06.png)

### Step 7

12. Create Run Configuration for WildFly - app should work if everything is configured correctly. 

![step 7](img/step07.png)
