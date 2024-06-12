- 👋 Hi, I’m @ibrahem1604h
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
  ```python
your_librarian =[]
your_wishlist =[]
x=input("Enter the name of a book you own: \t").lower()
your_librarian.append(x)
x2=input("Enter the name of book you own or press 'Enter' to skip)\t").lower()
if x2:
  your_librarian.append(x2)
  print(f"your library: {your_librarian}")
else:
  print(f"your library: {your_librarian}")
y=input("Enter the name of a book you wish to have in the future: \t").lower()
your_wishlist.append(y)
y2=input("Enter the name of another book you wish to have in the future or press 'Enter' to skip\t").lower()
if y2:
    your_wishlist.append(y2)
    print(f"your wishlist: {your_wishlist}")
else:
    print("")
    
z=input("Enter the name of a book from your wishlist that you have acquired or press 'Enter' to skip\t").lower()
if z:
    your_librarian.append(z)
    your_wishlist.remove(z)
    print(f"updated library: {your_librarian}")
    print(f"updated wishlist: {your_wishlist}")
else:
    print(f" library: {your_librarian}")
    print(f"wishlist: {your_wishlist}")

d=input("Enter the name of a book from your library you wish to donate or press 'Enter' to skip\t")
if d:
    your_librarian.remove(d)
    print(f"final library after donations: {your_librarian}")
else:
    print("")
<!---
ibrahem1604h/ibrahem1604h is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
