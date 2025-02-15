# <img src="https://github.com/user-attachments/assets/caabfdf0-0f9e-44a3-8200-c6579fe87887" alt="description icon" width="28"> Description
Repository created to store the authentication API code with the database.

# <img src="https://github.com/user-attachments/assets/2bd91f82-43a7-44c6-8fb3-eaa3ca20089e" alt="terminal icon" width="28"> Commands

## <img src="https://github.com/user-attachments/assets/10d3fd5b-ab3c-4ce0-bf22-68587cae9deb" alt="books icon" width="24"> Installing and updating dependencies
```
pip install -r requirements.txt --upgrade
```

## <img src="https://github.com/user-attachments/assets/ddfc24ed-a6e6-4975-b9df-e66091b743b5" alt="database icon" width="24"> Creating the database
### Using Flask commands
```
flask shell
```

### Indicating the creation of the database
```
db.create_all()
```

### Recording the creation of the database
```
db.session.commit()
```

### Exiting the terminal
```
exit()
```

## <img src="https://github.com/user-attachments/assets/df9d2ef7-42e7-4454-ac81-c92832d0c6dc" alt="user icon" width="24"> Creating the user
### Using Flask commands
```
flask shell
```

### Creating the user
```
user = User(username="CHOSEN_USERNAME", password="CHOSEN_PASSWORD")
```

### Adding the user
```
db.session.add(user)
```

### Recording the creation of the database
```
db.session.commit()
```

### Exiting the terminal
```
exit()
```
