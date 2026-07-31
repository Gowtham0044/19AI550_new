# Ex.No: 2  Welcome Script in Unity
### DATE: 31.07.2026                                                                           
### REGISTER NUMBER : 212224240046
### AIM: 
 To learn the basic scripting in Unity and print welcome message in Console window. 
### Procedure:
1. Start the program
2. Open the Unity hub and Create a new 3D project
3. In Assets window, create the new folder and name it as Scripts
4. Create a new script with file name as FirstScript
5. Open the Script and print message "Welcome to Unity" inside the start function
6. Save the script
7. Create a new 3D game object in Hierarchy window and name it as 3DObject.
8. Add the component Firstscript in inspector window of 3Dobject.
9. Run the program
10. Stop the program.
### Program 
```
using UnityEngine;

public class NewMonoBehaviourScript : MonoBehaviour
{
    // Start is called once before the first execution of Update after the MonoBehaviour is created
    void Start()
    {
        print("Welcome");
    }

    // Update is called once per frame
    void Update()
    {
        print("Welcome");
    }
}
```
### Output:
h<img width="1920" height="1080" alt="Screenshot 2026-07-24 131443" src="https://github.com/user-attachments/assets/ff64a7d0-6321-4735-a843-04b67b553884" />



### Result:
Thus the welcome script was printed on Console Window  sucessfully.
