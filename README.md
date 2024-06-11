# FormularioGUI
![](https://scontent.fgye30-1.fna.fbcdn.net/v/t1.15752-9/447673975_452324887399641_460487884294622372_n.png?_nc_cat=111&ccb=1-7&_nc_sid=5f2048&_nc_eui2=AeHz5D1IcGnvB4pXYiTLbKQmT_WDbqdMu9xP9YNup0y73A_ZX2VCnWNjE_oMs0rMDT9m4YlCvIaamSQlr1KSQJw1&_nc_ohc=Vm8fW__HMKcQ7kNvgGDK4tH&_nc_ht=scontent.fgye30-1.fna&oh=03_Q7cD1QFSTeHKUAmTPkIOlVrO2ABhI8ZQAPzz6NjjIoaj21qBJA&oe=668F23C2)

Este proyecto es una aplicación JavaFX que muestra un formulario con diversos controles de usuario comúnmente utilizados en interfaces gráficas de usuario (GUI). El objetivo principal es proporcionar un ejemplo práctico de cómo crear y organizar diferentes controles en una interfaz de usuario utilizando JavaFX.

## Explicación del código

El código fuente `Main.java` crea una instancia de `Application` y define el método `start` donde se construye la interfaz de usuario.

1. Se crea un `GridPane` para organizar los controles en una cuadrícula. Se configuran los espacios entre filas y columnas, y se establecen los márgenes.

2. Se definen dos `ColumnConstraints` para dividir el ancho del `GridPane` en dos columnas, una para los nombres de los controles (30% del ancho) y otra para los controles mismos (70% del ancho).

3. Se agregan etiquetas (`Label`) en la primera columna para identificar cada control.

4. En la segunda columna, se crean instancias de los siguientes controles y se agregan al `GridPane`:

  - `Button`
  - `CheckBox`
  - `Hyperlink`
  - `ToggleButton`
  - `RadioButton` (agrupados en un `ToggleGroup`)
  - `Label`
  - `TextField`
  - `PasswordField`
  - `TextArea`
  - `ProgressIndicator`
  - `ProgressBar`
  - `Slider`

5. Se crea una `Scene` a partir del `GridPane` y se establece en el `Stage` principal.

6. Se establece el título de la ventana y se configura para que no sea redimensionable.

7. Finalmente, se muestra la ventana (`Stage`) con la interfaz de usuario.

## Uso

Este proyecto puede ser utilizado como referencia para aprender cómo crear y organizar controles de usuario en una interfaz gráfica de usuario utilizando JavaFX. También puede servir como base para construir aplicaciones más complejas al agregar funcionalidad adicional a los controles y manejar eventos.

## Requisitos y ejecución

[Incluir aquí los requisitos y las instrucciones para ejecutar la aplicación, como en el README anterior]
