# assignment1
<!DOCTYPE html>
<html>
    <head>
        <title>HTML Form</title>
        <style>
            body {
                display: flex;
                justify-content: space-around;
                align-items: center;
                height: 100vh;
                margin: 0;
                background-image: url(data:image/jpeg;base64,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);
            }

            form {
                width: 400px;
                background-color: #0801051e;
                padding: 20px;
                border-radius: 8px;
                box-shadow: 0 0 10px
                    rgba(0, 0, 0, 0.1);
                    background-color: floralwhite;
            }

            fieldset {
                border: 1px solid black;
                padding: 10px;
                margin: 0;
            }

            legend {
                font-weight: bold;
                margin-bottom: 10px;
            }

            label {
                display: block;
                margin-bottom: 5px;
            }

            input[type="text"],
            input[type="email"],
            input[type="password"],
            textarea,
            input[type="date"] {
                width: calc(100% - 20px);
                padding: 8px;
                margin-bottom: 10px;
                box-sizing: border-box;
                border: 1px solid #ccc;
                border-radius: 4px;
            }

            input[type="radio"] {
                margin-left: 20px;
            }

            input[type="submit"] {
                padding: 10px 20px;

                border-radius: 5px;
                cursor: pointer;
            }
        </style>
    </head>
    <body>
        <form>
            <fieldset>
                <legend>
                    User personal information
                </legend>
                <label
                    >Enter your full name</label
                >
                <input type="text" name="name" />
                <label>Enter your email</label>
                <input
                    type="email"
                    name="email"
                />
                <label>Enter your password</label>
                <input
                    type="password"
                    name="pass"
                />
                <label
                    >Confirm your password</label
                >
                <input
                    type="password"
                    name="confirmPass"
                />
                <label>Enter your gender</label>
                <input
                    type="radio"
                    name="gender"
                    value="male"
                />Male
                <input
                    type="radio"
                    name="gender"
                    value="female"
                />Female
                <input
                    type="radio"
                    name="gender"
                    value="others"
                />Others
                <label
                    >Enter your Date of
                    Birth</label
                >
                <input type="date" name="dob" />
                <label>Enter your Address:</label>
                <textarea
                    name="address"
                ></textarea>
                <input
                    type="submit"
                    value="submit"
                />
            </fieldset>
        </form>
    </body>
</html>
