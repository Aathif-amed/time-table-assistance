# Time Table Assistance

## File Structure

- 📄 [README.md](README.md)
   - 📂 __api__
     - 📂 __info__
       - 📄 [departments.php](api/info/departments.php)
       - 📄 [faculties.php](api/info/faculties.php)
       - 📄 [faculty\_table.php](api/info/faculty_table.php)
       - 📄 [subjects.php](api/info/subjects.php)
     - 📂 __login__
       - 📄 [login.php](api/login/login.php)
       - 📄 [logout.php](api/login/logout.php)
     - 📂 __timetable__
       - 📄 [subject\_allocation.php](api/timetable/subject_allocation.php)
       - 📄 [time\_day.php](api/timetable/time_day.php)
       - 📄 [timetable.php](api/timetable/timetable.php)
   - 📂 __config__
     - 📄 [DbConnection.php](config/DbConnection.php)
   - 📂 __data__
     - 📄 [data.jsx](data/data.jsx)
     - 📄 [timetable.sql.gz](data/timetable.sql.gz)
   - 📂 __front\-end__
     - 📂 __css__
       - 📄 [style.css](front-end/css/style.css)
     - 📂 __img__
       - 📄 [avatar.png](front-end/img/avatar.png)
       - 📄 [avatar.svg](front-end/img/avatar.svg)
       - 📄 [bg.svg](front-end/img/bg.svg)
       - 📄 [tt1.png](front-end/img/tt1.png)
       - 📄 [wave.png](front-end/img/wave.png)
     - 📂 __js__
       - 📄 [login.js](front-end/js/login.js)
       - 📄 [logout.js](front-end/js/logout.js)
       - 📄 [main.js](front-end/js/main.js)
     - 📂 __public__
       - 📂 __assets__
         - 📄 [annaunivlogo.png](front-end/public/assets/annaunivlogo.png)
         - 📄 [banner.jpg](front-end/public/assets/banner.jpg)
         - 📄 [banner1.jpg](front-end/public/assets/banner1.jpg)
         - 📄 [tt.jpeg](front-end/public/assets/tt.jpeg)
       - 📂 __src__
         - 📄 [homepage.html](front-end/public/src/homepage.html)
         - 📄 [index.html](front-end/public/src/index.html)
         - 📄 [login.html](front-end/public/src/login.html)
   - 📂 __models__
     - 📄 [Admin.php](models/Admin.php)
     - 📄 [Faculty\_table.php](models/Faculty_table.php)
     - 📄 [Info.php](models/Info.php)
     - 📄 [Subject\_allocations.php](models/Subject_allocations.php)
     - 📄 [Time\_day.php](models/Time_day.php)
     - 📄 [Timetables.php](models/Timetables.php)
   - 📂 __utils__
     - 📄 [loggedin.php](utils/loggedin.php)
     - 📄 [send.php](utils/send.php)
