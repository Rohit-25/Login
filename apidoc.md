*GetAllUser/ 
(GET)> https://zany-teal-antelope-ring.cyclic.app/api/auth/users

/*Register/ 
(POST)> https://zany-teal-antelope-ring.cyclic.app/api/auth/register
(body) => {"name":"Rohit", "email":"rohit@gmail.com","password":"12345678","phone":343222432,role?":"user"}

/*Login/ 
(POST) => https://zany-teal-antelope-ring.cyclic.app/api/auth/login
(body) => {"email":"aa@gmail.com","password":"12345678"} (response)=> {auth:true,token:'dgsdg'}

/*UserInfo/ 
(GET) => https://zany-teal-antelope-ring.cyclic.app/api/auth/userinfo 
(Header) => {'x-access-token':'token value from login'}