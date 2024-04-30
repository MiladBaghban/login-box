<image align="right" alt="Milad" width = "400" src="https://webartdevelopers.com/blog/wp-content/uploads/2021/03/transparent-material-login-form.gif"> 
<pre>def authenticate(username, password): 
    if username == "admin" and password == "admin": 
        print("Welcome") 
    elif username == "admin": 
        print("Password is wrong") 
    else: 
        print("<{username}> is wrong and <{password}> check ") <br />

def main():
    username = input("Enter your username: ") 
    password = input("Enter your password: ") 
    authenticate(username, password) 

if __name__ == "__main__": 
    main() 
