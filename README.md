# oncfdeal
A script to list all ONCF train ticket prices and find the best (cheapest) option. Useful for comparing tickets quickly and saving money.

## How to Use

### Prerequisites
- Ensure you have a Unix-based system with a shell terminal.

### Usage
1. Clone the repository:
    ```bash
    git clone https://github.com/7h3Y055/oncfdeal.git
    cd oncfdeal
    ```

2. Add execution permission to the script:
    ```bash
    chmod +x oncfdeal
    ```

3. Run the script:
    ```bash
    ./oncfdeal
    ```

4. Follow the prompts to input your desired travel details (e.g., departure, destination, date, etc.).

5. The script will display a list of available train tickets along with their prices, highlighting the cheapest option.

### Example
```bash
./oncfdeal meknes fes
# Or you can use --date to specify the day
./oncfdeal meknes fes --date 05/04/2025
# If you have a student card
./oncfdeal meknes fes --student 123456789098765
```

The script will output:
```
Searching for tickets with a good price ...
-----------------------------------------------
|    DEPARTURE TIME    | ARRIVAL TIME | PRICE |
-----------------------------------------------
| 04/05/2025 01:28 AM  | 01:58 AM     | 25    |
| 04/05/2025 08:47 AM  | 09:27 AM     | 25    |
| 04/05/2025 11:18 AM  | 11:57 AM     | 30    |
| 04/05/2025 11:42 AM  | 12:20 PM     | 25    |
| 04/05/2025 12:39 PM  | 01:20 PM     | 25    |
| 04/05/2025 01:42 PM  | 02:20 PM     | 22    |
| 04/05/2025 02:39 PM  | 03:20 PM     | 25    |
| 04/05/2025 03:13 PM  | 03:51 PM     | 30    |
| 04/05/2025 03:42 PM  | 04:20 PM     | 22    |
| 04/05/2025 04:39 PM  | 05:22 PM     | 25    |
| 04/05/2025 05:42 PM  | 06:25 PM     | 25    |
| 04/05/2025 06:13 PM  | 06:51 PM     | 25    |
| 04/05/2025 06:42 PM  | 07:23 PM     | 25    |
| 04/05/2025 07:42 PM  | 08:25 PM     | 25    |
| 04/05/2025 08:39 PM  | 09:23 PM     | 25    |
| 04/05/2025 09:42 PM  | 10:20 PM     | 25    |
| 04/05/2025 10:39 PM  | 11:20 PM     | 25    |
| 04/05/2025 11:06 PM  | 11:39 PM     | 22    |
| 04/05/2025 11:36 PM  | 12:12 AM     | 25    |
-----------------------------------------------
```

### License
This project is licensed under the MIT License. See the `LICENSE` file for details.