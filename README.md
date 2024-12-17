# **5 Exámenes en CCOM**

## **¿Qué es 5 Exámenes en CCOM?**

 
### 5 Exámenes en CCOM es nuestro proyecto final para el curso de CCOM4995: Diseño de Videojuegos. Parte de nuestra inspiración viene de la icónica franquicia Five Nights at Freddy's de Scott Cawthon.

![image](https://github.com/user-attachments/assets/f9a7dfb9-efb6-4a2f-aab8-ba2999ad24d0)

### Este juego simula una pesadilla clásica para los estudiantes de Ciencia de Cómputos de la UPR-RP: ¡enfrentar un examen sin haber estudiado y depender de copiarse para pasar! Aunque toma elementos de horror y humor, 5 Exámenes en CCOM es único en sus mecánicas y está diseñado como un tributo a los estudiantes y profesores del Departamento de CCOM.

## **Objetivo del juego**
### Eres un estudiante desesperado en busca de 3 libretas con las respuestas del examen. Pero cuidado: el profesor, junto con la ayuda del perro Thor, patrullan el salón para asegurarse de que nadie se copie.

## **Reglas principales:**
### Recoge las 3 libretas con las respuestas para tu examen para avanzar al siguiente nivel. Si no recoges las 3 libretas, pierdes. Además, ser atrapado por el profesor resulta en una derrota inmediata. A medida que avanzas por las cinco escenas, la dificultad aumenta, reflejando la dificultad de los cursos a lo largo del Bachillerato en Ciencia de Cómputos.

# **Creación del Juego**

## **Assets Utilizados de la Tienda de Unity:**
### Desks Starter Collection
### GUI Parts
### Horror School Props
### Robot Hero: PBR HP Polyart
### Staff of Pain
### Animals_FREE
### Fire_Extinguiser
### NPC
### School Props
### AllSkyFree
### TextMeshPro

## Escena principal: Salon A-143: 
### El mapa principal del juego es una réplica del Salón A-143 del Departamento de CCOM. Para lograr el mayor realismo posible, tomamos fotografías de múltiples ángulos y de los objetos presentes en el salón. Esto nos permitió recrear el espacio con precisión, añadiendo detalles visuales que reflejan el ambiente del aula original.
![Salon](https://github.com/user-attachments/assets/f44e5be1-1298-416e-8b57-b47024ff8575) 

### Para organizar la construcción, dividimos el salón en seis subcategorías principales: piso, mesas, paredes, techo, decoraciones e iluminación.

## **Paso 1: Piso**

### El piso del salón es cuadriculado en la vida real. Iniciamos insertando un terreno ajustado y lo dividimos en cuadrículas utilizando una textura adecuada. Esto sirvió como base para construir el resto del salón.
![1](https://github.com/user-attachments/assets/380d2c70-98b8-4644-bd9d-966403c6028f)

## **Paso 2: Inserción de Personajes**

### Aprovechamos esta etapa para incluir los personajes principales que se usarán durante la escena:
### Jugador principal: Perro antropomórfico (primera persona).
### Thor: Perro animalístico, mascota del profesor Edusmildo Orozco.
### Profesores: Representados como figuras humanas.
![2](https://github.com/user-attachments/assets/a60e3d70-3b23-4b5e-ad2e-d4a2338aa8fe)

## **Paso 3: Mesas y Sillas**

### Creamos los prefabs de las mesas y descargamos los de las sillas del salón. Lo hicimos basándonos en las fotografías capturadas, al igual que sus texturas. Este paso fue crucial porque determinó las proporciones internas del espacio. La creación fue hecha una vez diseñados los prefabs; los duplicamos y posicionamos con distancias adecuadas entre ellos, incluyendo mesas auxiliares.
![3](https://github.com/user-attachments/assets/4cb7ce47-315d-44ae-b833-d06ecfaa18e5)
![4](https://github.com/user-attachments/assets/947d4f77-72f6-4683-9207-2b4cdf4c041d)

## **Paso 4: Paredes**

### Pared Izquierda

### La creación de las paredes no fue complicada, a excepción de la pared que contiene las ventanas del salón (la pared de la izquierda, considerando que la pared frontal es la que contiene las pizarras). Esta pared requirió mayor atención debido a que contiene ventanas, cortinas y espacios internos con muchas esquinas. Utilizamos figuras ajustadas con las herramientas de Game Object para crearla.
![5](https://github.com/user-attachments/assets/b6b56553-b39f-4030-b28b-e564e7924176)

### Pared Frontal
## Contiene pizarras y el whiteboard utilizado para proyectar presentaciones.
![6](https://github.com/user-attachments/assets/eed6ac13-1b36-4a49-afe9-b0ece6e85dc1)

### Pared Derecha
### No requirió muchos detalles adicionales, más allá de decoraciones menores.
![7](https://github.com/user-attachments/assets/f2c29fdc-a88b-44c7-b9d7-5ae3c4ade52d)

### Pared Trasera 
### Incluye interruptores, sensores de temperatura, pupitres adicionales, receptáculos eléctricos y un extintor con su cartel correspondiente.
![8](https://github.com/user-attachments/assets/4382ec98-52cb-4cf5-833c-f3830f668c29)

### Al finalizar las paredes, el salón comienza a tomar forma.
![9](https://github.com/user-attachments/assets/1e1f5649-bf55-48b1-a73a-8ca2f46e033e)

## **Paso 5 Techo**

### Creamos el techo utilizando un plano dividido en cuadrículas con la herramienta ProBuilder de Unity. Aplicamos texturas obtenidas de fotografías y ajustamos los espacios en la pared izquierda. Además, se añadieron elementos como luces, puntos de acceso WiFi y rejillas de ventilación. Posteriormente, colocamos scripts para que las luces hagan efectos de parpadeo.
![10](https://github.com/user-attachments/assets/6cd4d872-8373-4a2b-814c-e16d858b1cd4)
![11](https://github.com/user-attachments/assets/dfedcb29-15e2-4568-a465-8efe16fda338)

## **Paso 6: Decoraciones**

### En la pared trasera incluimos breakers, sensores, pupitres adicionales y un extintor con cartel.
![12](https://github.com/user-attachments/assets/8c8077cc-2ec9-4039-b92d-b35cc1114254)

### Para la pared de la izquierda, añadimos una silla azul y receptáculos eléctricos.
![13](https://github.com/user-attachments/assets/a4a32124-0d39-4661-bea9-545931af3fbe)

### Finalmente, en la pared de la derecha, solo se añadió un receptáculo adicional.
![15](https://github.com/user-attachments/assets/8fda4a91-05fd-4d94-8643-bfcab0a456c9)

## **Paso 7: Iluminación**
### Optamos por crear un salón oscuro para aumentar la suspensión y el temor. Aplicamos un skybox nocturno para generar escasez de luz. Además, añadimos un script de parpadeo a cada luz, de modo que la única iluminación en el juego sea inconsistente. Este script incluye delays ajustables entre los niveles máximo y mínimo de intensidad, así como el parpadeo. También configuramos qué luces se encenderán según el nivel del juego. A continuación, presentamos el script implementado:
![18](https://github.com/user-attachments/assets/d1c31f08-42cc-433b-a1e6-ac61c955acb9)
![19](https://github.com/user-attachments/assets/2f3976d6-9f4e-40f7-9f32-776b19b93d4d)
![20](https://github.com/user-attachments/assets/a2199c25-06cd-4182-a54f-e56f1f424af4)

![LightFlickering](https://github.com/user-attachments/assets/3a33ac3b-0b88-42ee-ac7a-47af10b3bd12)


### Por último, añadimos colisionadores a los objetos interactuables del salón, completando su creación. Copiamos esta escena final y la utilizamos para los próximos niveles, cambiando el lugar de las libretas. Pensamos que quedaría simple, pero estamos orgullosos del resultado final. Aquí una foto para comparar con la inicial.
![16](https://github.com/user-attachments/assets/d389b14b-d70e-4fa6-bf52-f8d42b649460)

## Jugador Principal:

### Se utilizó el prefab Supercyan Character Pack Animal People Sample que se descargó en el Unity Asset Store. Se le agregaron la configuración de las teclas para el movimiento (A, W, S, D) y la configuración de la letra E (Take) para interactura con las libretas. Luego se le añadieron los scripts de PlayerMovement y PlayerPickUpDrop, respectivamente. para que este último funcionara adecuadamente, se crearon los layers de Jugador y Libreta. Se le dio al script como argumento el layer de Libreta y se agregó al prefab. Además, se le añadió el layer al jugador. 

![Movimiento](https://github.com/user-attachments/assets/21082daf-546d-4d2a-b555-33c1c067f0b6)

### Libretas:

### Las libretas, además de poseer el script de PlayerPickUpDrop, que permite al jugador tomar la libreta (borrar el objeto) para poder pasar de nivel, utiliza el script ObjectGrabbable que toma el objeto de la libreta como argumento para trabajar con el script anterior. Aunque también, poseen su propio Manager (NotebookManager) que evalúa la cantidad de libretas que no han sido tomadas (o destruidas) para saber si el jugador cumple con la condición de victoria.

### Tiempo

### Se hizo un canvas que tuviera el contador y se hizo un código para manejar el tiempo que sale en el contador. 

![TiempoScript](https://github.com/user-attachments/assets/26279f15-7347-427c-af3b-79045c778223)
![codigo2timer](https://github.com/user-attachments/assets/3e440ba2-d4b9-4288-87f4-fa4ad6b9b03d)

![counter](https://github.com/user-attachments/assets/6a7c8d52-f09f-4f96-b449-733205df8e2f)


## Enemigos:

## Pantallas de Victoria y Derrota
### Uno de los elementos más creativos de 5 Exámenes en CCOM son las pantallas finales, creadas con la colaboración de profesores del Departamento de CCOM. Estas incluyen fotografías en dos versiones: una feliz y otra molesta. Las imágenes fueron decoradas con elementos humorísticos, como objetos, imágenes y videos, para mantener un tono ligero y respetuoso hacia los profesores. Además, utilizamos una tipografía similar a la de Five Nights at Freddy's, obtenida de www.dafont.com, para reforzar la estética del juego.

### Tipos de Escenas: 
### Escena introductoria: Antes de cada partida, se muestra la clase, el curso, el profesor y la hora.

### Victoria final: Una pantalla cómica que celebra el triunfo del jugador.

### Derrota 1: Si no recoges ninguna libreta, se refleja el fracaso con un mensaje irónico.

![losescreen1](https://github.com/user-attachments/assets/00867c03-ad40-45cb-a825-fe452d834ef2)

### Derrota 2: Si te atrapan copiándote, el profesor aparece molesto por tus acciones. 

![losescreen2](https://github.com/user-attachments/assets/9232b9eb-a1ea-472a-9f1c-38eaf17d36bd)

![Cheo](https://github.com/user-attachments/assets/e1b6dfa2-56e5-4367-9697-dfa29487fcc4)


## Agradecimientos

### Agradecemos profundamente a los siguientes profesores, y mascotas, del Departamento de Ciencias de Cómputos por su apoyo y colaboración al permitir el uso de sus imágenes en el juego:
### Edusmildo Orozco y su perro Thor
### Rafael Arce
### David Flores
### Ivelisse Rubio
### José Ortiz
### Humberto Ortiz
### Lillian González
