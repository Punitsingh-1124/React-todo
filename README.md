# React-todo
Overview of Your Code

#Key Features


1 Add Todos: Users can add tasks (minimum 3 characters) via an input field.

2 Edit Todos: Edit existing tasks by clicking the edit button.

3 Delete Todos: Remove tasks with a delete button.

4 Mark as Complete/Incomplete: Toggle a task’s status with a checkbox (applies strikethrough).

5 Show/Hide Completed Tasks: Filter out completed tasks using the Show Finished toggle.

6 Persistent Storage: Todos are saved in localStorage for persistence across reloads.
![Screenshot 2024-11-21 135048](https://github.com/user-attachments/assets/e32540ac-1848-43dc-8c5c-b127e4f106a9)



#Tailwind CSS Highlights


1 Responsive Design: The container adapts to screen sizes using classes like md:container and md:w-[35%].

2 Stylish Buttons: Buttons have hover (hover:bg-violet-950) and disabled (disabled:bg-violet-600) states.

3 Input Field: Fully styled with rounded-full, px-5 py-1, and w-full.

![Screenshot 2024-11-21 135321](https://github.com/user-attachments/assets/a45626da-d720-4146-bff3-46b9403e186c)


#Functionality


1 Todos are fetched from localStorage on load (useEffect).

2 Tasks are dynamically updated in the UI and saved to localStorage.

3 Completed tasks are visually differentiated with a strikethrough.
