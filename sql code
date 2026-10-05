CREATE DATABASE RideBooking;
USE RideBooking;

CREATE TABLE Users (
    user_id INT PRIMARY KEY,
    name VARCHAR(30),
    phone VARCHAR(15)
);

CREATE TABLE Rides (
    ride_id INT PRIMARY KEY,
    user_id INT,
    pickup VARCHAR(50),
    destination VARCHAR(50),
    fare INT,
    status VARCHAR(20)
);

INSERT INTO Users VALUES
(1, 'Ashmita', '9876543210'),
(2, 'Rahul', '9876501234');

INSERT INTO Rides VALUES
(101, 1, 'College', 'Bus Stand', 150, 'Completed'),
(102, 2, 'Market', 'Railway Station', 100, 'Booked');

SELECT * FROM Users;
SELECT * FROM Rides;