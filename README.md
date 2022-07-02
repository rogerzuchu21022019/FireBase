# FireBaseDatabase

# Type1 : Get 


# Type2 : Push
1 Để push lên thì cần có Model để gửi lên -> Tạo class Model

2 Cần có ImageName và ImageURL để có thể 

1 Push id
```
Model Upload upload = Upload(filename,imageURL)
String uploadID = mDatabaseRef.push.getKey()
mDatabaseRef.child(uploadID).setValue(upload)
```
