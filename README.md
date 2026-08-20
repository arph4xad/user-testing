## Test project details
Values to use when creating your project and z/OS Asset in the prototype:
- **API project name:** Catalog API
- **z/OS Asset name:** catalogManager
- **z/OS Asset type:** CICS COMMAREA

<details>

<summary>Example JSONata mappings to try out</summary>
<br/>

- **Request mappings** - 
    For the `CA-QUANTITY` field in the z/OS Asset request, try writing a JSONata mapping that ensures an invalid quantity cannot be sent:
    ```
    If quantity is greater than 0, use quantity; otherwise use 1
    ```
    
- **Response conditions** - 
    For the 201 response of your operation, try writing a JSONata condition that sends the 201 response if the following is true:
    ```
    Return code equals 0 and response message contains "SUCCESS" 
    ```

</details>

<img width="1380" height="1666" alt="Frame 12341820" src="https://github.com/user-attachments/assets/c36c764d-5f75-4314-b4dd-c62cf8f05406" />

<img width="1380" height="3049" alt="Frame 12341821" src="https://github.com/user-attachments/assets/7393855a-cbdb-4f7e-8aa7-40f25ff4accf" />

<img width="1380" height="1159" alt="Frame 12341822" src="https://github.com/user-attachments/assets/1ef90686-aba2-420b-b63a-d6ba34814c84" />


