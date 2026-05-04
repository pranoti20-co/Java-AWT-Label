# 🏷️ Java AWT - Label Component

A simple Java program demonstrating the **Label component** in AWT.

---

## 📌 What is Label?

A **Label** is a GUI component used to display **non-editable text**.

✔ Cannot be edited by user  
✔ Used for titles, messages, instructions  

---

## 🎯 Features

- Display text using Label
- Simple GUI window
- Beginner-friendly example

---

## 🧠 Alignment Types

- LEFT → Left aligned text
- CENTER → Center aligned text
- RIGHT → Right aligned text

---

## ⚙️ Code Example

```java
import java.awt.*;

class LabelDemo {
    public static void main(String args[]) {
        Frame f = new Frame("Label Example");

        Label l1 = new Label("Hello Label");

        l1.setBounds(100, 100, 100, 30);

        f.add(l1);

        f.setSize(300, 200);
        f.setLayout(null);
        f.setVisible(true);
    }
}
## 🖥️ output
 ![Output](Screenshot_2026-05-04-18-37-2407_c37d74246d9c81aa0bb824b57eaf7062.jpg )
