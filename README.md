## Programs 📝


- Draw a line in a diagram from position (1, 3) to position (8, 10):

  ```py
  import matplotlib.pyplot as plt

  x = [1, 8]
  y = [3, 10]

  plt.plot(x, y)
  plt.show()
  ```
  ![1](https://github.com/user-attachments/assets/699c58ea-1405-4c2a-aa76-8890a01c6f77)








- Draw two points in the diagram, one at position (1, 3) and one in position (8, 10):

  ```py
  import matplotlib.pyplot as plt

  x = [1,8]
  y = [3,10]

  plt.plot(x,y,'o')
  plt.show()
  ```
  ![2](https://github.com/user-attachments/assets/c4634b35-b663-475d-bfc0-ba8f810fff22)








- Draw a line in a diagram from position (1, 3) to (2, 8) then to (6, 1) and finally to position (8, 10):

  ```py
  import matplotlib.pyplot as plt
  
  x = [1,2,6,8]
  y = [3,8,1,10]

  plt.plot(x,y)
  plt.show()
  ```
  
  ![download](https://github.com/user-attachments/assets/c06532c0-3155-4b36-8e5d-9d54b1bfe275)









  ### Default X-Points
  
  - If we do not specify the points on the x-axis, they will get the default values 0, 1, 2, 3 etc., depending on the length of the y-points.

  ```py
  import matplotlib.pyplot
  
  y = [3, 8, 1, 10, 5, 7]
  
  plt.plot(y)
  plt.show()
  ```

  ![download](https://github.com/user-attachments/assets/f03e8ca1-1467-4722-8f11-88a59e8dc272)
