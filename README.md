# OTP-Verification-System
Introduction  
The OTP Verification System enhances security during user authentication by generating a random 6-digit OTP, sending it to the user's email, and verifying the input within a limited number of attempts.  

Features  
Generates a random 6-digit OTP  
Sends OTP via email  
Verifies user-entered OTP  
Limits verification attempts (max 3 attempts)  

Implementation Overview  
Programming Language - Python  

Key Libraries  
random – OTP generation  
smtplib & email.message – Sending OTP via email  

System Flow  
OTP Generation  
Email Sending  
User Input  
OTP Verification  

Key Functions  
generate_otp(): Generates a 6-digit random OTP  
send_email(to_mail, otp): Sends OTP via email  
verify_otp(otp, user_input): Verifies the entered OTP  
main(): Integrates all functions and executes the system flow  

Challenges & Solutions  
1. Handling Invalid Email Addresses  
Solution: Implement try-except error handling.  

2. Preventing Unlimited Attempts  
Solution: Restrict OTP verification attempts to 3.  

Conclusion  
Successfully implemented a secure OTP verification system with robust test cases.  

