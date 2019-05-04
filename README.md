# hello-me
repository Python labs
using the index function
for name in names:
    print(name,'is found at index' , names.index(name)) #printing all name along with index
names = ["Ben","Tom","Jerry","Wiki","Sylwi","Kevin"]
print(names)
raw_newIndex = input('Please enter index to replace:')
newIndex = int(raw_newIndex)  
newName = input('Please enter name to put in index:')
names[newIndex] = newName
print(names) 
newName = input('Enter new name to add to list:')
names.append(newName)
print(names)
remName = input('Enter name to remove')
names.remove(remName)
print(names)
