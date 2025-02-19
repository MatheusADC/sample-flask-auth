# <img src="https://github.com/user-attachments/assets/caabfdf0-0f9e-44a3-8200-c6579fe87887" alt="description icon" width="28"> Description
Repository created to store the authentication API code with the database.

# <img src="https://github.com/user-attachments/assets/2bd91f82-43a7-44c6-8fb3-eaa3ca20089e" alt="terminal icon" width="28"> Commands

## <img src="https://github.com/user-attachments/assets/9bd14bb5-8e8c-4050-ac18-1383038c84a5" alt="books icon" width="24"> Installing and updating dependencies
```
pip install -r requirements.txt --upgrade
```

## <img src="https://github.com/user-attachments/assets/f8992568-f0e4-4f98-84f1-c877ff0d471b" alt="database icon" width="24"> Creating the database
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
