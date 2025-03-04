<!DOCTYPE html>
<html lang="uk">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Перевірка віку</title>
</head>
<body>
    <script>
        let age = prompt("17:");
        age = Number(age);
        
        if (isNaN(age)) {
            alert("17");
        } else if (age < 18) {
            alert("Вам заборонено вхід");
        } else if (age >= 18 && age <= 65) {
            alert("Ласкаво просимо!");
        } else {
            alert("Будь ласка, будьте обережні!");
        }
    </script>
</body>
</html>
