## Interfaces

        function updateAge(user: {birthdate: Date, age: number}):void {
            if (moment().dayOfYear() === moment(user.birthdate).dayOfYear()) {
                user.age++;
            }
        }

