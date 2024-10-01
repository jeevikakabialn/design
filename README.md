<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Admission Form</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>
    <div class="container mt-5">
        <h2 class="text-center">Admission Form</h2>
        <form>
            <div class="row mb-3">
                <div class="col-md-6">
                    <label for="firstName" class="form-label">First Name</label>
                    <input type="text" class="form-control" id="firstName" placeholder="Enter First Name">
                </div>
                <div class="col-md-6">
                    <label for="lastName" class="form-label">Last Name</label>
                    <input type="text" class="form-control" id="lastName" placeholder="Enter Last Name">
                </div>
            </div>
            <div class="row mb-3">
                <div class="col-md-6">
                    <label for="fatherName" class="form-label">Father's Name</label>
                    <input type="text" class="form-control" id="fatherName" placeholder="Enter Father's Name">
                </div>
                <div class="col-md-6">
                    <label for="dob" class="form-label">Date of Birth</label>
                    <input type="date" class="form-control" id="dob">
                </div>
            </div>
            <div class="row mb-3">
                <div class="col-md-6">
                    <label for="gender" class="form-label">Gender</label>
                    <select class="form-control" id="gender">
                        <option>Select Gender</option>
                        <option>Male</option>
                        <option>Female</option>
                        <option>Other</option>
                    </select>
                </div>
                <div class="col-md-6">
                    <label for="email" class="form-label">Email</label>
                    <input type="email" class="form-control" id="email" placeholder="Enter Email">
                </div>
            </div>
            <div class="row mb-3">
                <div class="col-md-6">
                    <label for="phone" class="form-label">Phone Number</label>
                    <input type="tel" class="form-control" id="phone" placeholder="Enter Phone Number">
                </div>
                <div class="col-md-6">
                    <label for="address" class="form-label">Address</label>
                    <input type="text" class="form-control" id="address" placeholder="Enter Address">
                </div>
            </div>
            <div class="row mb-3">
                <div class="col-md-6">
                    <label for="nationality" class="form-label">Nationality</label>
                    <input type="text" class="form-control" id="nationality" placeholder="Enter Nationality">
                </div>
                <div class="col-md-6">
                    <label for="highSchoolMarks" class="form-label">High School Marks</label>
                    <input type="text" class="form-control" id="highSchoolMarks" placeholder="Enter High School Marks">
                </div>
            </div>
            <div class="row mb-3">
                <div class="col-md-6">
                    <label for="previousQualification" class="form-label">Previous Qualification</label>
                    <input type="text" class="form-control" id="previousQualification" placeholder="Enter Previous Qualification">
                </div>
                <div class="col-md-6">
                    <label for="yearOfPassing" class="form-label">Year of Passing</label>
                    <input type="number" class="form-control" id="yearOfPassing" placeholder="Enter Year of Passing">
                </div>
            </div>
            <div class="row mb-3">
                <div class="col-md-6">
                    <label for="admissionID" class="form-label">Admission ID</label>
                    <input type="number" class="form-control" id="admissionID" placeholder="Enter Admission ID">
                </div>
                <div class="col-md-6">
                    <label for="courseID" class="form-label">Course ID</label>
                    <input type="number" class="form-control" id="courseID" placeholder="Enter Course ID">
                </div>
            </div>
            <div class="row mb-3">
                <div class="col-md-6">
                    <label for="applicationDate" class="form-label">Application Date</label>
                    <input type="date" class="form-control" id="applicationDate">
                </div>
                <div class="col-md-6">
                    <label for="confirmPassword" class="form-label">Confirm Password</label>
                    <input type="password" class="form-control" id="confirmPassword" placeholder="Confirm Password">
                </div>
            </div>
            <div class="row mb-3">
                <div class="col-md-6">
                    <label for="guardianPhone" class="form-label">Guardian's Phone Number</label>
                    <input type="tel" class="form-control" id="guardianPhone" placeholder="Enter Guardian's Phone Number">
                </div>
                <div class="col-md-6">
                    <label for="disability" class="form-label">Any Disability</label>
                    <select class="form-control" id="disability">
                        <option>No</option>
                        <option>Yes</option>
                    </select>
                </div>
            </div>
            <div class="row mb-3">
                <div class="col-md-6">
                    <label for="hostelRequired" class="form-label">Hostel Required</label>
                    <select class="form-control" id="hostelRequired">
                        <option>No</option>
                        <option>Yes</option>
                    </select>
                </div>
            </div>
            <button type="submit" class="btn btn-primary">Submit</button>
        </form>
    </div>
</body>
</html>

cass
body {
    background-color: #f8f9fa; /* Light background color */
}

.container {
    background-color: #ffffff; /* White background for the form container */
    border-radius: 8px; /* Rounded corners */
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); /* Subtle shadow for depth */
    padding: 30px; /* Spacing inside the container */
}

h2 {
    margin-bottom: 20px; /* Space below the heading */
    color: #343a40; /* Dark color for the heading */
    font-weight: 600; /* Bold font for the heading */
}

.form-label {
    font-weight: 500; /* Medium font weight for labels */
    color: #495057; /* Dark gray color for labels */
}

.btn-primary {
    background-color: #007bff; /* Custom blue background for the button */
    border: none; /* Remove default border */
    padding: 10px 20px; /* Padding inside the button */
    font-size: 16px; /* Font size for button text */
}

.btn-primary:hover {
    background-color: #0056b3; /* Darker blue on hover */
}

input[type="text"],
input[type="email"],
input[type="tel"],
input[type="date"],
input[type="number"],
select {
    border: 1px solid #ced4da; /* Light border color */
    border-radius: 4px; /* Rounded corners for inputs */
}

input[type="text"]:focus,
input[type="email"]:focus,
input[type="tel"]:focus,
input[type="date"]:focus,
input[type="number"]:focus,
select:focus {
    border-color: #80bdff; /* Highlight border color on focus */
    outline: none; /* Remove default outline */
}

.row {
    margin-bottom: 15px; /* Space between rows */
}
