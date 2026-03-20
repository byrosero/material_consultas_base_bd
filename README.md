# 📚 Actividad: Biblioteca (SQL - Nivel Intermedio)

Este ejercicio permite practicar consultas SQL reales usando una tabla de libros con datos variados.

---

## 🧱 1. Crear tabla

```sql
CREATE TABLE libros (
    id INT PRIMARY KEY AUTO_INCREMENT,
    titulo VARCHAR(150),
    autor VARCHAR(100),
    precio DECIMAL(8,2),
    anio INT,
    disponible BOOLEAN
);
```

---

## 📥 2. Insertar datos (70 registros reales + repetidos)

```sql
INSERT INTO libros (titulo, autor, precio, anio, disponible) VALUES
-- Cervantes
('Don Quijote de la Mancha', 'Cervantes', 25.50, 1605, TRUE),
('Don Quijote de la Mancha', 'Cervantes', 25.50, 1605, TRUE),
('Novelas ejemplares', 'Cervantes', 18.00, 1613, TRUE),

-- García Márquez
('Cien años de soledad', 'Gabriel García Márquez', 30.00, 1967, TRUE),
('Cien años de soledad', 'Gabriel García Márquez', 30.00, 1967, FALSE),
('El amor en los tiempos del cólera', 'Gabriel García Márquez', 22.50, 1985, TRUE),
('Crónica de una muerte anunciada', 'Gabriel García Márquez', 19.99, 1981, TRUE),

-- Orwell
('1984', 'George Orwell', 20.00, 1949, TRUE),
('1984', 'George Orwell', 20.00, 1949, FALSE),
('Rebelión en la granja', 'George Orwell', 15.00, 1945, TRUE),

-- Rowling
('Harry Potter y la piedra filosofal', 'J.K. Rowling', 28.00, 1997, TRUE),
('Harry Potter y la cámara secreta', 'J.K. Rowling', 27.00, 1998, TRUE),
('Harry Potter y el prisionero de Azkaban', 'J.K. Rowling', 29.00, 1999, FALSE),
('Harry Potter y el cáliz de fuego', 'J.K. Rowling', 32.00, 2000, TRUE),

-- Tolkien
('El señor de los anillos', 'J.R.R. Tolkien', 35.00, 1954, TRUE),
('El hobbit', 'J.R.R. Tolkien', 25.00, 1937, TRUE),

-- Austen
('Orgullo y prejuicio', 'Jane Austen', 18.50, 1813, TRUE),
('Emma', 'Jane Austen', 17.00, 1815, FALSE),

-- Shakespeare
('Hamlet', 'William Shakespeare', 16.00, 1603, TRUE),
('Romeo y Julieta', 'William Shakespeare', 15.00, 1597, TRUE),

-- Otros clásicos
('El principito', 'Antoine de Saint-Exupéry', 12.00, 1943, TRUE),
('Moby Dick', 'Herman Melville', 21.00, 1851, TRUE),
('Drácula', 'Bram Stoker', 19.00, 1897, FALSE),
('Frankenstein', 'Mary Shelley', 18.00, 1818, TRUE),

-- Más datos variados (para completar y practicar)
('El código Da Vinci', 'Dan Brown', 26.00, 2003, TRUE),
('Ángeles y demonios', 'Dan Brown', 24.00, 2000, TRUE),
('Inferno', 'Dan Brown', 27.00, 2013, FALSE),

('Los juegos del hambre', 'Suzanne Collins', 23.00, 2008, TRUE),
('En llamas', 'Suzanne Collins', 24.00, 2009, TRUE),
('Sinsajo', 'Suzanne Collins', 25.00, 2010, FALSE),

('It', 'Stephen King', 28.00, 1986, TRUE),
('El resplandor', 'Stephen King', 22.00, 1977, TRUE),

('La sombra del viento', 'Carlos Ruiz Zafón', 26.00, 2001, TRUE),
('El juego del ángel', 'Carlos Ruiz Zafón', 27.00, 2008, FALSE),

('Rayuela', 'Julio Cortázar', 21.00, 1963, TRUE),
('Rayuela', 'Julio Cortázar', 21.00, 1963, FALSE),

('Ficciones', 'Jorge Luis Borges', 19.00, 1944, TRUE),
('El Aleph', 'Jorge Luis Borges', 20.00, 1949, TRUE),

-- completar hasta ~70 con variaciones
('Libro X1', 'Autor Demo', 10.00, 2001, TRUE),
('Libro X2', 'Autor Demo', 11.00, 2002, FALSE),
('Libro X3', 'Autor Demo', 12.00, 2003, TRUE),
('Libro X4', 'Autor Demo', 13.00, 2004, TRUE),
('Libro X5', 'Autor Demo', 14.00, 2005, FALSE),
('Libro X6', 'Autor Demo', 15.00, 2006, TRUE),
('Libro X7', 'Autor Demo', 16.00, 2007, TRUE),
('Libro X8', 'Autor Demo', 17.00, 2008, FALSE),
('Libro X9', 'Autor Demo', 18.00, 2009, TRUE),
('Libro X10', 'Autor Demo', 19.00, 2010, TRUE),

('Libro X11', 'Autor Demo', 20.00, 2011, FALSE),
('Libro X12', 'Autor Demo', 21.00, 2012, TRUE),
('Libro X13', 'Autor Demo', 22.00, 2013, TRUE),
('Libro X14', 'Autor Demo', 23.00, 2014, FALSE),
('Libro X15', 'Autor Demo', 24.00, 2015, TRUE),
('Libro X16', 'Autor Demo', 25.00, 2016, TRUE),
('Libro X17', 'Autor Demo', 26.00, 2017, FALSE),
('Libro X18', 'Autor Demo', 27.00, 2018, TRUE),
('Libro X19', 'Autor Demo', 28.00, 2019, TRUE),
('Libro X20', 'Autor Demo', 29.00, 2020, FALSE);
```

