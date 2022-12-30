# Command Line Test

## Introduction:
Command-Line Test is a BASH Shell based tool that simulates Login-based Online Testing scenario. Initially, the User will be provided with a Sign-in option where pre-defined Users will be allowed to Login. Upon successful Login, this tool will display Questions for the particular logged-in User from existing data-base. It will also handle Error conditions like Time-out. This tool will also store Answers provided by the particulat logged-in User for future verification.

These days there are a lot of Online Test platform which enables Students to take Tests Online. They will typically have a User-interface, Backend Question Bank and Evaluation mechanism. They will also support other features like pre-defined Time per Question, Output Reports etc. The idea of this project is to simulate such an Online Test Interface using Linux Shell Scripting and Commands. 

By implementing this Linux Shell Scripting Project, we make use of Shell programming constructs (eg: loops), Pattern matching commands (eg: grep, sed etc.) and File-handling (eg: permission, directories etc.) aspects during implementation.

## Requirements:
**Provide a prompt for the user to Sign-up and Sign-in:**
1. Sign In<br>
a. Take Test<br>
b. View Test<br>
2. Sign up
3. Exit

**Using sign-up user can register with a User-ID and Password:**
1. Ask for User-name. The User-name should contain only Alpha-Numeric symbols.<br>
2. Ask for new Password. The Password can contain any symbol in it. Accept at-least 8 characters with at-least a Number and Symbol.<br>
3. Ask the User to re-enter the Password again for validation.<br>

**Already Registered User can Sign-in with ID and Password:**
1. The Script should prompt for User-name and Password.<br>
2. The Password should be like a Shadow Password (i.e. characters shall be blank while typing).<br>
3. Show Error in-case the 2 Passwords mismatch.<br>

**Create Log-file:**
1. Every activity while the Script is to be Logged in test_activity.log file.<br>
2. Keep Date and Time along with every Activity.<br>

**Question bank:**
1. User should provide a Question Bank file along with the Script.<br>
2. If not, Search for a file named question_bank.txt as a Default Question Bank.

**Taking a test:**
1. Should create a directory called “.TestData” in User’s Directory structure. For eg.: ECEP/LinuxSystems/Projects directory if it doesn’t exist.<br>
2. Create a file named “answer_file.csv” under TestData directory if it doesn’t exist.<br>
3. Prompt the User with Questions one by one randomly picked from the question_bank.txt file.<br>
4. Prompt for Questions with Multiple choice.<br>
5. Every Question should be Timed, say 10 seconds.<br>
6. On time-out, the Question should change with fresh time-out.<br>
7. Every answer should be stored in answer_file.csv with the Question separated by comma.<br>
8. The answer should be stored with Attempt time. Eg.: If I answer within 5 seconds, then my answer with 5 seconds (Attempt time) should be stored.<br>
9. If the User chooses one Option, the Script should show all the Questions with all Options and the Answer should be highlighted.

**Time-out:**
1. The Script should Time-out if the User Input is absent for more than 10 seconds on the Main Menu.<br>

## Snapshots:
![image](https://user-images.githubusercontent.com/108017134/210093814-cd1a3f03-ef8e-4775-95d8-433842fbc669.png)
![image](https://user-images.githubusercontent.com/108017134/210093826-147e7d4f-4026-4417-9080-561a758ebac3.png)
![image](https://user-images.githubusercontent.com/108017134/210093833-017c39aa-564a-4cbe-a4c3-91b69c327fd4.png)
![image](https://user-images.githubusercontent.com/108017134/210093848-cdc9fa99-d02c-4e1d-a1ba-db827117aacf.png)
![image](https://user-images.githubusercontent.com/108017134/210093911-6d1b7a97-221d-4b49-b57c-fe9c8403916a.png)
![image](https://user-images.githubusercontent.com/108017134/210093921-bdd5fee4-6e0b-48c0-9f7e-206d76e66cc1.png)
![image](https://user-images.githubusercontent.com/108017134/210093934-b5abd1b9-800b-4943-9bf8-9d5096cbd5e6.png)
![image](https://user-images.githubusercontent.com/108017134/210093940-6c4075cc-20c0-44de-858c-c1455528cd04.png)
![image](https://user-images.githubusercontent.com/108017134/210093945-946047b5-ad9e-49b7-a9fb-7fd3f660a4ce.png)
![image](https://user-images.githubusercontent.com/108017134/210093954-56255385-7b7d-4bfb-a249-cfa3d0b7604e.png)
![image](https://user-images.githubusercontent.com/108017134/210093965-ad5cb308-76e8-4ffd-8023-b8305e152eb8.png)
![image](https://user-images.githubusercontent.com/108017134/210093970-8090f1e2-76a2-46e5-a0f4-009188631ba7.png)
![image](https://user-images.githubusercontent.com/108017134/210093979-6f36d6e2-aa03-4a6a-a0d0-371fa1a77202.png)
![image](https://user-images.githubusercontent.com/108017134/210093994-20778bf8-2a87-4789-add4-2029c0d4b196.png)
![image](https://user-images.githubusercontent.com/108017134/210094008-46b65a0c-3356-4cd3-bef2-b0b2d2344abc.png)
