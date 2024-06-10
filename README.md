# This project was a part of coursework for a course on C++, wherein the group has worked to emulate a booking system used in the university.
## Groupmates: Ananya Chenny Rahul, Anannya Umesh, Arunima Srikant (author), Ayesha Rao, Radhika Kamdar
1. Use Replit Desktop.
2. There are two different user types that can access the booking system – an admin and a student. We will begin with the user being a student. The student mail must be of the form: firstname.lastname@uni.edu.in. Since we are emulating the booking process of a specific university, unless the email doesn't match this format, you will not be able to make a booking.
3. After the email is entered, you will be given 4 options; 1. Book by room, 2. Book by time, 3. Cancel Booking and 4. Exit.
4. With each booking, it will start removing those options of the rooms or timings already booked from the options. For example, I have booked Room1 for 9:00 AM, and when I want to book by room again, and I choose Room1 again, in the next step, the time, 9:00 AM will not exist as an option since it’s already booked. (make sure you correctly enter the timings, otherwise, it will not work)
5. You can try the same with the “book by timing” function. 
6. Once you start booking rooms, a CSV tab will open on Replit which will store the data. Click on the CSV tab to cross-check the bookings
7. You can cancel the booking and check if the room can be booked again.
8. This is the student side. Now let's try the Admin side. 
9. For admin side, the mail id should end with “@admin.uni.edu.in” (for eg, firstname.lastname@admin.uni.edu.in)
10. Now, you will have one more option other than ones students get called “Reset Bookings” wherein the admin can clear out the bookings.
11. Reset booking can only be allowed after we enter a password. The password in this case is “radhikaanannya123”. 
