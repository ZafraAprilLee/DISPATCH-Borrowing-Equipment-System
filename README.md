# **DISPATCH**

A school equipment borrowing system, built with Java Swing.

Ever tried to borrow a projector or an extension cord from a school office and ended up with a paper form, a missing signature, and no idea whether anyone actually saw your request? DISPATCH is our answer to that. Students and teachers request equipment, the admin approves it, and everything is tracked from the first click to the day the item comes back.

It's a desktop app with no database and no server. Everything lives in plain text files, which keeps it easy to run and easy to understand.

# **Users**
> **For students and teachers**
 
• Sign up and sign in with a 10-digit ID (the admin has to register your ID first, so random people can't make accounts)

• Browse equipment and see what's available, borrowed, or under repair

• Send a borrow request with the quantity you need and your proof

• Track your requests through each stage: Pending, Approved, Borrowed, Returned, Overdue, Rejected, or Expired

• View a receipt once your request is approved, then show it at the admin office to pick up your item

• Manage your profile: upload a photo (PNG or JPG, up to 5 MB), edit your details, change your password

• Ask for help if you forgot your password or want your account deleted


> **For the admin**


• Dashboard with live counts of total, available, borrowed, overdue, and pending items

• Equipment management: add, edit, delete, and filter items, with images

• Request handling: approve, reject, release items to borrowers, and mark returns

• Damage and loss charges on return: a damaged item costs half its price, a lost item costs the full price, and late returns add a per-day penalty. The app works out the amount due and the change.

• Borrowing rules you can adjust on the fly: max quantity per student and teacher, max borrow days, pickup window, and late penalty

• User management: add student and teacher IDs, change their status, reset passwords, and delete accounts

• Blocked users: accounts get blocked after 3 failed logins (or manually by the admin), and the admin can unblock them

• Deletion requests: users can ask to have their account removed, and the admin approves or rejects

# **Data Structure**

• FIFO Queue for requests

• Binary search & Selection sort for looking up equipment and requests by ID

• Insertion sort to keep users ordered by ID

• ArrayList of Objects for Users and Equipments

# **OOP Concepts Applied**

• Abstraction

• Inheritance

• Polymorphism

• Encapsulation

# **Screenshots**
<p align="center">Login Page</p>
<br>
<p align="center">
<img width="740" height="479" alt="Dispatch Log In Pic" src="https://github.com/user-attachments/assets/c6453d41-7978-480e-a571-49efa2e49e8b" />
</p>
<p align="center">Create Account Page</p>
<br>
<p align="center">
<img width="740" height="478" alt="Dispatch Sign Up Pic" src="https://github.com/user-attachments/assets/1d5efc8d-fe7f-4fcb-8a88-ee3e853b5b2f" />
</p>
<p align="center">Browse Equipment Page</p>
<br>
<p align="center">
<img width="959" height="539" alt="Browse" src="https://github.com/user-attachments/assets/70b46d6d-0652-41b3-8136-010b9af8b4a6" />
</p>
<br>
<p align="center">My Request Page</p>
<br>
<p align="center">
<img width="959" height="539" alt="Request Pic" src="https://github.com/user-attachments/assets/c76ea874-ea63-442b-b7c8-8d0342b104e8" />
</p>
<br>
<p align="center">Profile Page</p>
<br>
<p align="center">
<img width="959" height="539" alt="Profile Pic" src="https://github.com/user-attachments/assets/91c3d484-b8c4-4348-a40b-dfcfadcb3ac0" />
</p>
<br>
<p align="center">Admin Dashboard Page</p>
<br>
<p align="center">
<img width="959" height="535" alt="Admin Dashboard" src="https://github.com/user-attachments/assets/7eb12d9e-3cd8-486c-b570-9d6b0da7d948" />
</p>
<br>
<p align="center">Admin Equipment Page</p>
<br>
<p align="center">
<img width="959" height="539" alt="Equipment Page" src="https://github.com/user-attachments/assets/5aa3c0cb-0c46-40ea-9d83-4843b2c91368" />
</p>
<br>
<p align="center">Add Equipment Page</p>
<br>
<p align="center">
<img width="959" height="539" alt="Add Equipment Page" src="https://github.com/user-attachments/assets/30fbab87-70e2-4e1c-858c-0cbf81a7173e" />
</p>
<br>
<p align="center">Edit Equipment Page</p>
<br>
<p align="center">
<img width="959" height="539" alt="Edit Equipment Page" src="https://github.com/user-attachments/assets/e07a72d6-c267-43cf-a9cc-7c695f2035dd" />
</p>
<br>
<p align="center">Admin Request Page</p>
<br>
<p align="center">
<img width="959" height="538" alt="Request Admin Page" src="https://github.com/user-attachments/assets/40c96ba0-e935-4533-868e-d2b01e390a3e" />
</p>
<br>
<p align="center">Admin System Page</p>
<br>
<p align="center">
<img width="959" height="478" alt="System Part 1" src="https://github.com/user-attachments/assets/c5950635-6b27-4701-9eb7-5e3f169ed0fa" />
</p>
<br>
<p align="center">Admin System Table Page</p>
<br>
<p align="center">
<img width="959" height="539" alt="Student Table" src="https://github.com/user-attachments/assets/dd4c1537-e05c-4a31-a953-87fb995025aa" />
</p>

# **Contributing**

Found a bug or have an idea? Open an issue or send a pull request. Small fixes are very welcome.
