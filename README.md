# **Guess the Rectangle Game**  

This Python project is an interactive game where the user guesses whether a point falls inside a randomly generated rectangle and estimates its area. It uses **OOP (Object-Oriented Programming)** concepts and the **`turtle` graphics module** for visualization.

---

## **Features**
1. **Random Rectangle Generation**: 
   - A rectangle with random coordinates is generated each time the game runs.  
   - The rectangle is visualized on a black background using the `turtle` graphics module.

2. **User Interaction**:  
   - The user inputs a point (x, y) and guesses whether it falls inside the rectangle.  
   - The user also guesses the area of the rectangle.

3. **Validation**:  
   - The program checks whether the user’s point is inside the rectangle.  
   - It calculates the difference between the guessed area and the actual area.

4. **Visual Feedback**:  
   - The rectangle and guessed point are displayed graphically.  
   - The point is drawn in red, and the rectangle is outlined in violet.

---

## **Code Explanation**

### **Classes**
1. **`Point`**:
   - Represents a point with `x` and `y` coordinates.
   - Provides a method to check if it falls within a given rectangle.

2. **`Rectangle`**:
   - Represents a rectangle using two points: the lower-left and upper-right corners.
   - Provides a method to calculate its area.

3. **`GuiRectangle`**:
   - Extends `Rectangle` and adds a `draw` method to visualize the rectangle using `turtle`.

4. **`GuiPoint`**:
   - Extends `Point` and adds a `draw` method to visualize the point using `turtle`.

### **Main Logic**
1. **Random Object Creation**:
   - A rectangle and its corners are generated randomly.
2. **User Input**:
   - The user enters a point’s coordinates and guesses the rectangle’s area.
3. **Output**:
   - The program prints whether the point lies inside the rectangle.
   - The error in the area guess is displayed.
4. **Visualization**:
   - The rectangle and point are displayed using the `turtle` module.

---

## **How to Run**
1. **Install Python**:
   Ensure Python 3 is installed on your system.

2. **Run the Script**:
   Save the code in a `.py` file (e.g., `guess_rectangle.py`) and run it in a Python environment.

3. **Interact**:
   - Enter your guesses for the point and rectangle area when prompted.
   - Watch the rectangle and point being drawn on the screen.

---

## **Customization**
- Change the rectangle’s range by modifying the `randint` values in `GuiRectangle` and `Rectangle`.
- Adjust the point size or color in `GuiPoint.draw()` for better visibility.
- Enhance the game by adding scoring or multiple rounds.

---

## **Example Usage**
```
Rectangle Coordinates: 100, 50 and 300, 250
Guess X: 150
Guess Y: 100
Guess Rectangle area:  40000
Your point was inside rectangle: True
Your areas were off by: -20000
```

---

## **Requirements**
- Python 3.x
- `turtle` module (included in Python’s standard library)

---

Enjoy learning Python and visualizing your programs!
