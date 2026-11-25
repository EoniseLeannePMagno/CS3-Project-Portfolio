# WORKSHEET 2
## Identify Objects, Classes, and Relationships

**Instructions:** Use the process and proposed system from Worksheet 1 to complete this worksheet.

---

## Part 1. Identify the Objects

Identify the important people, things, records, transactions, or concepts that your proposed system needs to represent.

**Guide Question:**

If you were going to create a program for this process, what things would the program need to represent?

| No. | Object | Description |
|:---:|---|---|
| 1 | hi| i|
| 2 | | |
| 3 | | |
| 4 | | |
| 5 | | |

### Object Evaluation

For each identified object, ask:

- Does it play an important role in the process?
- Does it contain information?
- Does it perform an action?
- Does it interact with another object?
- Does the proposed system need to keep track of it?

**Reminder:** Remove objects that are not necessary for your proposed system.

---

## Part 2. Analyze Object Interactions

Determine how your identified objects interact with one another.

**Example:** `Student → submits → Request`

| No. | Object 1 | Interacts | Object 2 |
|:---:|---|---|---|
| 1 | | | |
| 2 | | | |
| 3 | | | |
| 4 | | | |
| 5 | | | |
| 6 | | | |
| 7 | | | |
| 8 | | | |

---

## Part 3. Identify Possible Classes

Determine which objects can become classes in your proposed system.

Not every object needs to become a class. Choose only the objects that are important to your proposed system.

| No. | Class | What does it represent? |
|:---:|---|---|
| 1 | Student | The person that will borrow equipment
| 2 | Staff | The one that will handle the equipment |
| 3 | Equipment | The item being borrowed by students |

---

## Part 4. Class Analysis

Analyze the attributes and methods of each identified class.

### Class No. 1

**Class Name:** Student

**Purpose:**  
Represents the one who will borrow the Sports Equipment
#### Attributes

| Attribute | Description |
|---|---|
| Name | Name of Student |
| Grade And Section | Grade and Section of Student |
| ID Number | Verifies if the Student is in PSHS-DRC or not |
| Date of Borrow | Date when the Sports Equipment was borrowed |
| Expected Date of Return | The expected date when the Sports Equipment will be returned |
| Actual Date of Return | Actual date when the Sports Equipment was returned |

#### Methods

| Method Name | What does it do? |
|---|---|
| Display Equipment | Displays the available Sports Equipment |
| Borrow Equipment | Displays notification of the borrowed Sports Equipment, Displays the date and time of borrowing |
| Return Equipment | Displays notification of the due date for the Sports Equipment, Displays the actual date and time of return |

---

### Class No. 2

**Class Name:** Staff

**Purpose:**  
The person that handles equipment and monitors the Tracker

#### Attributes

| Attribute | Description |
|---|---|
| Name | Name of Staff Member |
| ID Number | ID number of Staff Member |
| Department | Department of Staff Member |
| Position | Position of Staff Member |

#### Methods

| Method Name | What does it do? |
|---|---|
| Equipment Tracker | Displays the available Sports Equipment, the borrowed and the damaged |
| Confirm of Borrowed Equipment | Allows them to borrow the available requested Sports Equipment, Determines the date and time of borrowing |
| Notify Equipment Due Date | Gives notification of the due date for the Sports Equipment |
| Confirmation Of Returned Equipment | Logs in the actual time and date of return, confirms the return of Sports Equipment |

### Class No. 3

**Class Name:** Equipment

**Purpose:**  
The Sports Equipment being borrowed

#### Attributes

| Attribute | Description |
|---|---|
| Name | Name of Sports Equipment |
| Type | Type of Sports Equipment |
| Sport | Designated Sport of Equipment |
| Count | Amount of Sports Equipment available |
| Status | Determines if the Sports Equipment is borrowed, available, or damaged |

#### Methods

| Method Name | What does it do? |
|---|---|
| Equipment Tracker | Displays the available, the borrowed, and the damaged Sports Equipment |
| Update Status | Changes the status of the Sports Equipment |
| Update Count | Updates the count of the Sports Equipment after borrowing |

---

**Additional Classes:** Add another copy of the Class Analysis section for each additional class you identify.

**Reminder:** Keep your project simple. Avoid creating unnecessary classes.

---

## Part 5. Identify Class Relationships

Determine how your identified classes are related to one another.

| No. | Class 1 | Relationship | Class 2 | Why are they related? |
|:---:|---|---|---|---|
| 1 | | | | |
| 2 | | | | |
| 3 | | | | |
| 4 | | | | |
| 5 | | | | |
| 6 | | | | |

### Relationship Types

| Relationship | Description |
|---|---|
| **Association** | Two classes interact with one another. |
| **Aggregation** | One class groups or contains objects that can exist independently. |
| **Composition** | One class strongly owns another object. |
| **Inheritance** | One class is a specialized version of another class. |

**Reminder:** Use only the relationship types that make sense for your proposed system. Not all relationship types are required.
