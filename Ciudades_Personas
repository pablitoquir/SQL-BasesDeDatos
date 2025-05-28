--Hacer la base de datos 
CREATE DATABASE IF NOT EXISTS personas_ciudades;
USE personas_ciudades;

-- Tabla de ciudades
CREATE TABLE ciudades (
    id INT AUTO_INCREMENT PRIMARY KEY,
    nombre VARCHAR(100) NOT NULL,
    pais VARCHAR(100) NOT NULL
);

-- Tabla de personas
CREATE TABLE personas (
    id INT AUTO_INCREMENT PRIMARY KEY,
    nombre VARCHAR(100) NOT NULL,
    edad INT NOT NULL,
    ciudad_id INT,
    FOREIGN KEY (ciudad_id) REFERENCES ciudades(id)
);
