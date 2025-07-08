# Styled_Profile_Card
## Date: 08/07/2025

## Objective:
To practice HTML and CSS fundamentals by designing a visually appealing profile card that demonstrates the use of background color, typography, spacing, and layout alignment techniques.

## Tasks:
#### 1. Create the HTML Structure:
Use ```<!DOCTYPE html>, <html>, <head>, and <body>``` to define the structure.
Add a ```<title>``` like "My Profile Card".

#### 2. Add Content:
Include name, title (e.g., Developer, Student), and a short bio using semantic tags such as ```<h1>```, ```<h2>```, and ```<p>```.

#### 3. Add a Profile Image:
Use the ```<img>``` tag to include a profile picture with appropriate alt, width, and height attributes.

#### 4. Apply Background Color:
Use a CSS class to style the card with a background color.

#### 5. Style Typography:
Use CSS to apply different font families, sizes, and text colors for the name and bio.

#### 6. Add Spacing:
Apply margin and padding to improve spacing between elements using CSS.

#### 7. Center the Card:
Use flexbox or margin: auto to center the card vertically and horizontally on the page.

#### 8. Add Hover Effects:
Enhance interactivity with simple hover effects like border changes or background transition using CSS.

## HTML Code:
```

body {
  background-color: #f0f0f0;
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  margin: 0;
  padding: 20px;
}


.profile-card {
  background-color: #ffffff;
  max-width: 400px;
  margin: 40px auto;
  padding: 30px;
  text-align: center;
  border-radius: 12px;
  box-shadow: 0 4px 15px rgba(0, 0, 0, 0.1);
}


.profile-card img {
  border-radius: 50%;
  display: block;
  margin: 0 auto 20px auto;
  box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
}


h1 {
  font-size: 28px;
  color: #333333;
  margin-bottom: 10px;
}

h2 {
  font-size: 18px;
  color: #777777;
  margin-bottom: 20px;
}


.bio {
  background-color: #fafafa;
  padding: 15px;
  border-radius: 8px;
  line-height: 1.6;
  color: #555555;
}


hr {
  border: none;
  border-top: 1px solid #dddddd;
  margin: 20px 0;
}

```
## Output:
![image](https://github.com/user-attachments/assets/305d6d97-e50e-4504-8199-cdd8268f1dd3)

## Result:
A visually appealing profile card that demonstrates the use of background color, typography, spacing, and layout alignment techniques is designed.
