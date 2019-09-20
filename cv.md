> [GitHub](https://github.com/nurdared) |
[nurda9727@gmail.com](mailto:nurda9727@gmail.com) | 
[+7(702)568-48-37](tel: +77025684837)

# Nurdaulet Shamilov 
I want to be qualified Web-Developer, currently I am studying very hard in order to improve my skills and grow every day, Knowledge is the most powerful weapon, If you know more, you can do more, there is not any boundaries, I think to be successful, human have to be self-motivated and work hard every day.

## Skills
- **Web Development:** HTML, CSS, JavaScript, PHP, Laravel, Bootstrap 4, ASP.NET Core, Azure Web Sevices, MVC
- **Programming Languages:** Java, C++, C#
- **Database:** MSSQL, MySQL
- **Testing tools:** Selenium WebDriver, TestNG, Extent Report

## Code Examples
**Task:** _Create function that will count occurences of given element inside of given array_
```javascript
function countOccurrences(array, searchElement) {
  return array.reduce((accumulator, current) => {
    const occurrence = (current === searchElement) ? 1 : 0;
    console.log(accumulator, current, searchElement);
    return accumulator + occurrence;
  }, 0);
}
```