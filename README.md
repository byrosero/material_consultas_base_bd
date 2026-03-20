# BIBLIOTECA


---

## 1. Crear tabla

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

## 2. Insertar datos

```sql
INSERT INTO libros (titulo, autor, precio, anio, disponible) VALUES
INSERT INTO libros (titulo, autor, precio, anio, disponible) VALUES
('Don Quijote de la Mancha', 'Miguel de Cervantes', 25.50, 1605, TRUE),
('Novelas ejemplares', 'Miguel de Cervantes', 18.00, 1613, TRUE),
('La Galatea', 'Miguel de Cervantes', 15.00, 1585, FALSE),

('Cien años de soledad', 'Gabriel García Márquez', 30.00, 1967, TRUE),
('El amor en los tiempos del cólera', 'Gabriel García Márquez', 22.00, 1985, TRUE),
('Crónica de una muerte anunciada', 'Gabriel García Márquez', 19.50, 1981, TRUE),

('1984', 'George Orwell', 20.00, 1949, TRUE),
('Rebelión en la granja', 'George Orwell', 14.50, 1945, TRUE),

('El principito', 'Antoine de Saint-Exupéry', 12.00, 1943, TRUE),

('Harry Potter y la piedra filosofal', 'J.K. Rowling', 28.00, 1997, TRUE),
('Harry Potter y la cámara secreta', 'J.K. Rowling', 27.00, 1998, TRUE),
('Harry Potter y el prisionero de Azkaban', 'J.K. Rowling', 29.00, 1999, FALSE),

('El hobbit', 'J.R.R. Tolkien', 25.00, 1937, TRUE),
('El señor de los anillos', 'J.R.R. Tolkien', 35.00, 1954, TRUE),

('Orgullo y prejuicio', 'Jane Austen', 18.00, 1813, TRUE),
('Emma', 'Jane Austen', 17.00, 1815, FALSE),

('Hamlet', 'William Shakespeare', 16.00, 1603, TRUE),
('Romeo y Julieta', 'William Shakespeare', 15.00, 1597, TRUE),

('Moby Dick', 'Herman Melville', 21.00, 1851, TRUE),
('Drácula', 'Bram Stoker', 19.00, 1897, FALSE),

('Frankenstein', 'Mary Shelley', 18.50, 1818, TRUE),
('It', 'Stephen King', 28.00, 1986, TRUE),
('El resplandor', 'Stephen King', 22.00, 1977, TRUE),

('El código Da Vinci', 'Dan Brown', 26.00, 2003, TRUE),
('Ángeles y demonios', 'Dan Brown', 24.00, 2000, TRUE),

('Inferno', 'Dan Brown', 27.00, 2013, FALSE),

('Los juegos del hambre', 'Suzanne Collins', 23.00, 2008, TRUE),
('En llamas', 'Suzanne Collins', 24.00, 2009, TRUE),
('Sinsajo', 'Suzanne Collins', 25.00, 2010, FALSE),

('Rayuela', 'Julio Cortázar', 21.00, 1963, TRUE),
('Ficciones', 'Jorge Luis Borges', 19.00, 1944, TRUE),
('El Aleph', 'Jorge Luis Borges', 20.00, 1949, TRUE),

('La sombra del viento', 'Carlos Ruiz Zafón', 26.00, 2001, TRUE),
('El juego del ángel', 'Carlos Ruiz Zafón', 27.00, 2008, FALSE),

('Ensayo sobre la ceguera', 'José Saramago', 23.00, 1995, TRUE),
('El nombre de la rosa', 'Umberto Eco', 22.00, 1980, TRUE),

('Lolita', 'Vladimir Nabokov', 21.00, 1955, TRUE),
('Ulises', 'James Joyce', 24.00, 1922, FALSE),

('Madame Bovary', 'Gustave Flaubert', 20.00, 1857, TRUE),
('La metamorfosis', 'Franz Kafka', 18.00, 1915, TRUE),

('El extranjero', 'Albert Camus', 19.00, 1942, TRUE),
('La peste', 'Albert Camus', 20.00, 1947, TRUE),

('El viejo y el mar', 'Ernest Hemingway', 17.00, 1952, TRUE),
('Por quién doblan las campanas', 'Ernest Hemingway', 23.00, 1940, FALSE),
('Cien años de soledad', 'Gabriel García Márquez', 30.00, 1967, FALSE),
('1984', 'George Orwell', 20.00, 1949, FALSE),
('El principito', 'Antoine de Saint-Exupéry', 12.00, 1943, FALSE),
('Rayuela', 'Julio Cortázar', 21.00, 1963, FALSE),
('It', 'Stephen King', 28.00, 1986, FALSE),

('La tregua', 'Mario Benedetti', 18.00, 1960, TRUE),
('Gracias por el fuego', 'Mario Benedetti', 19.00, 1965, TRUE),

('Pedro Páramo', 'Juan Rulfo', 20.00, 1955, TRUE),
('El llano en llamas', 'Juan Rulfo', 18.50, 1953, FALSE),

('El túnel', 'Ernesto Sabato', 17.00, 1948, TRUE),
('Sobre héroes y tumbas', 'Ernesto Sabato', 22.00, 1961, TRUE),

('La ciudad y los perros', 'Mario Vargas Llosa', 24.00, 1963, TRUE),
('La fiesta del chivo', 'Mario Vargas Llosa', 26.00, 2000, TRUE),

('La casa de los espíritus', 'Isabel Allende', 23.00, 1982, TRUE),
('Eva Luna', 'Isabel Allende', 22.00, 1987, FALSE),

('El alquimista', 'Paulo Coelho', 19.00, 1988, TRUE),
('Brida', 'Paulo Coelho', 18.00, 1990, TRUE),

('Los miserables', 'Victor Hugo', 25.00, 1862, TRUE),
('Nuestra señora de París', 'Victor Hugo', 24.00, 1831, FALSE),

('Anna Karenina', 'León Tolstói', 26.00, 1877, TRUE),
('Guerra y paz', 'León Tolstói', 30.00, 1869, TRUE);
```

