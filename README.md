# readme1
test papers

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Salary Calculator</title>
</head>
<body>
    <h1>Salary Calculator</h1>
    <form action="/calculate" method="post">
        <label for="base_salary">Base Salary:</label>
        <input type="number" step="0.01" name="base_salary" required><br>

        <label for="bonus">Bonus:</label>
        <input type="number" step="0.01" name="bonus"><br>

        <label for="deductions">Deductions:</label>
        <input type="number" step="0.01" name="deductions"><br>

        <input type="submit" value="Calculate">
    </form>
</body>
</html>
