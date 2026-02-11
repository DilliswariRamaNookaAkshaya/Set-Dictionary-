# Palindrome 
a = {"abba", "bbaa", "abbaba", "bbaabb"}

print("Palindrome strings are:")
for word in a:
    if word == word[::-1]:
        print(word)

#Dictionary
Data= {
    101: "Akshaya",
    102: "Ravi",
    103: "Sita",
    104: "Swathi",
    105: "Mounika"
}

roll_no = int(input("Enter roll number: "))

if roll_no in Data:
    print("User exists in data")
    print("Name:", Data[roll_no])
    print("Roll No:", roll_no)
else:
    print("User not found in data")
    name = input("Enter user name: ")
    Data[roll_no] = name
    print("User added successfully")
    print("Name:", name)
    print("Roll No:", roll_no)
