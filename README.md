# Student Grade Manager - JavaFX Application

This is a simple JavaFX-based GUI application that allows users to input student names and scores, calculate average, highest, and lowest scores, and display a summary report with a pie chart visualization.

## Features

* ✅ GUI-based input of student names and scores
* 📊 Calculation of:

  * Total number of students
  * Average score
  * Highest and lowest score with names
* 📋 Summary report generation
* 🍰 Pie chart visualization of student scores
* 💾 Export:

  * Save summary report as a `.txt` file
  * Save pie chart as a `.png` image
* 📈 Sorted student scores (high to low)

## How to Run

### Prerequisites

* Java JDK 17+
* JavaFX SDK (Download from: [https://gluonhq.com/products/javafx/](https://gluonhq.com/products/javafx/))

### Project Structure

```
├── src
│   ├── StudentGradeManagerFX.java
│   ├── StudentController.java
│   ├── Student.java
├── resources
│   └── layout.fxml
├── lib
│   └── (include JavaFX JARs here)
```

### Compilation Command

```
javac --module-path "/path/to/javafx-sdk/lib" --add-modules javafx.controls,javafx.fxml -d out src/*.java
```

### Run Command

```
java --module-path "/path/to/javafx-sdk/lib" --add-modules javafx.controls,javafx.fxml -cp out StudentGradeManagerFX
```

Replace `/path/to/javafx-sdk/lib` with the actual path to your JavaFX `lib` directory.

## Author

* Developed by: Mohit
* Contact: [mohitp1208@gmail.com](mailto:mohitp1208@gmail.com)

---

Feel free to modify and extend this project for learning or academic use.
