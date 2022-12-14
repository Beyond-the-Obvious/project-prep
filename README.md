# project-prep
prep work for 301-final project 

# Trello Board Link
https://trello.com/b/Sl0QVoah/handify-project

# Wireframe Images #


![1 Home Page](https://user-images.githubusercontent.com/108029468/184314272-56f91b41-f71d-42e4-8f7d-2b84503a8fde.png)


![2 Sign in](https://user-images.githubusercontent.com/108029468/184314280-2d028872-8034-42fb-82c9-611d1a8a2eaf.png)


![3 User Dashboard](https://user-images.githubusercontent.com/108029468/184314289-4c744135-c371-4e61-a755-718e3faae7b9.png)


![4 My Favorite List](https://user-images.githubusercontent.com/108029468/184314295-0f422944-20a8-4830-95d8-295dd770c4fa.png)


![5 My items](https://user-images.githubusercontent.com/108029468/184314305-17524425-8165-497b-834c-b223b034280a.png)


![6 Purchase history](https://user-images.githubusercontent.com/108029468/184314313-90df0a48-6fb8-4e97-8f87-0f8aa84b02de.png)


![7 Settings](https://user-images.githubusercontent.com/108029468/184314320-4ac44f1a-e2fa-44e4-91eb-dfdc7e1efec6.png)

<hr>
<hr>
<hr>
<hr>

# Domain Modeling Diagram #

![Domain Modeling Diagram](https://user-images.githubusercontent.com/108029468/184316526-570e6fb7-9177-4df2-92d6-0c7a69c59fce.png)

<hr>
<hr>
<hr>
<hr>

# Schema # 

```
{
  "title": "Item registration form",
  "description": "Please enter your Items details.",
  "type": "object",
  "required": [
    "itemName",
    "itemDescription",
    "itemPrice",
    "itemImgUrl"
  ],
  "properties": {
    "itemName": {
      "type": "string",
      "title": "Name",
      "default": ""
    },
    "itemDescription": {
      "type": "string",
      "title": "Description"
    },
    "itemPrice": {
      "type": "number",
      "title": "Price",
      "minLength": 10
    },
    "itemImgUrl": {
      "type": "string",
      "title": "ImageUrl"
    }
  }
}
```

![Schema Model Diagram](https://user-images.githubusercontent.com/108029468/184324689-2879e760-96ba-4b84-9cf7-cee342d83a5e.png)

