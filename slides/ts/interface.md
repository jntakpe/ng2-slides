## Interfaces

        function updateAge(user: {birthdate: Date, age: number}):void {
            if (moment().dayOfYear() === moment(user.birthdate).dayOfYear()) {
                user.age++;
            }
        }

| 
  
        interface Writer {
            write(message: string): void;    
        }
        
        
        function writeUserName(writer: Writer) {
            writer.write(this.user.name);
        }
