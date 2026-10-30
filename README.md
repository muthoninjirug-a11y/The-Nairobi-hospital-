# The-Nairobi-hospital-
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>THE NAIROBI HOSPITAL</title>
</head>
<body>

    <header>
        <h1>OUTPATIENT MEDICAL SERVICES</h1>
        <p>Welcome to Nairobi Hospital where We provide quality healthcare services to all outpatients.</p>
    </header>

    <hr>

    <main>
        <section>
            <h2>Patient Registration</h2>
            <p>All patients must register before receiving medical services.</p>

            <form action="#" method="POST">
                <label for="fullname">Full Name:</label><br>
                <input type="text" id="fullname" name="fullname" required><br><br>

                <label for="age">Age:</label><br>
                <input type="number" id="age" name="age" required><br><br>

                <label>Gender:</label><br>
                <input type="radio" id="gender-male" name="gender" value="Male">
                <label for="gender-male">Male</label>
                <input type="radio" id="gender-female" name="gender" value="Female">
                <label for="gender-female">Female</label>
                <br><br>

                <label for="phone">Phone Number:</label><br>
                <input type="tel" id="phone" name="phone" required><br><br>

                <label for="email">Email Address:</label><br>
                <input type="email" id="email" name="email" required><br><br>

                <label for="service">Medical Service Required:</label><br>
                <select id="service" name="service">
                    <option value="general">General Consultation</option>
                    <option value="dental">Dental Services</option>
                    <option value="eye">Eye Check-up</option>
                    <option value="paediatric">Paediatric Services</option>
                    <option value="laboratory">Laboratory Services</option>
                </select>
                <br><br>

                <input type="submit" value="Register">
                <input type="reset" value="Clear">
            </form>
        </section>

        <hr>

        <section>
            <h2>Available Medical Services and Consultation Fees</h2>

            <table border="1">
                <thead>
                    <tr>
                        <th>Medical Service</th>
                        <th>Doctor</th>
                        <th>Day</th>
                        <th>Time</th>
                        <th>Consultation Fee (KSh)</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>General Consultation</td>
                        <td>Dr. cindy Kamau</td>
                        <td>Monday</td>
                        <td>8:00 AM - 12:00 PM</td>
                        <td>Ksh.1,000</td>
                    </tr>
                    <tr>
                        <td>Dental Services</td>
                        <td>Dr. lukelysia Wanjiru</td>
                        <td>Tuesday</td>
                        <td>9:00 AM - 1:00 PM</td>
                        <td>Ksh.3000</td>
                    </tr>
                    <tr>
                        <td>Eye Check-up</td>
                        <td>Dr. Muthoni Njiru</td>
                        <td>Wednesday</td>
                        <td>10:00 AM - 2:00 PM</td>
                        <td>Ksh.1500</td>
                    </tr>
                    <tr>
                        <td>Paediatric Services</td>
                        <td>Dr. patrick Njiru</td>
                        <td>Thursday</td>
                        <td>8:00 AM - 12:00 PM</td>
                        <td>Ksh.2000</td>
                    </tr>
                    <tr>
                        <td>Laboratory Services</td>
                        <td>Dr. Timothy joseph</td>
                        <td>Friday</td>
                        <td>9:00 AM - 3:00 PM</td>
                        <td>Ksh.500</td>
                    </tr>
                </tbody>
            </table>
        </section>
    </main>

    <hr>

    <footer>
        <h2>Contact Us</h2>
        <p>Phone: 0140149463</p>
        <p>Email: info@the nairobi hospital.com</p>
        <p>Location: Nairobi, Kenya</p>
        <p>&copy; 2026 The nairobi Hospital. All Rights Reserved.</p>
    </footer>

</body>
</html>
