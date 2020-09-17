# Mikhail Shemchuk
# Contacts
   - **Tel.:** +375 29 714-54-74 (A1)
   - **E-mail:** [mihey.by@gmail.com](mailto:mihey.by@gmail.com)
   - **Skype:** mihey.by
   - **Telegram:** [Mikhail Sh](https://t.me/Michael_S3)

   # Summary
   My first goal - to explore the profession of web-developer. 
   I would like to work in a team of professionals, in a friendly and confidential atmosphere. We will sing 'Kumbaya' and worship cats together. 
   My strength: communicability, calmness, responsibility, management skills.
   I have like swimming, riding a bike, to play guitar, and other activities. 
   Several years engaged in social dance (Blues, Salsa, Bachata, Lindi-Hop).
   Not married. 

   # Code sample
   ```javascript
    /**
    * @param preferences - an array of integers. Indices of people, whom they love
    * @returns number of love triangles
    */
    module.exports = function getLoveTrianglesCount(preferences = []) {
    let count = 0;

    preferences = preferences.map( item => item - 1);

    for (let i = 0; i < preferences.length; i++) {
        first = preferences[i]; //whom love first lover
        second = preferences[first];  //whom love second lover
        third = preferences[second];  //whom love third lover

        //if 3rd lover love 1st lover in chain - then it's a love triangle
        if ((i == third) && (first != second) && (second != third)) {
        preferences[i] = -1;  //exclude this triangle from cheking
        preferences[first] = -1;
        preferences[third] = -1;
        count++;
        }
    }

    return count;
    };
   ```

   # Skills 
   - JS
   - HTML5 / CSS3
   - SQL
   - Git
   - Figma
   - С / C++
   - Delphi 
   - Java
   - SQLite
   - VB
   - Windows
   - Linux

   # Experience
   Creation of software for cashboxes on Delphi (create modules and DLL). 
   Software development of the following systems:
   - client-server application to automate the collection and storage of data from impulse meters OWEN SI8 in the poultry workshop of "Vitkonproduct" JLLC (Delphi);
   - client-server application software for automation, collection and storage of feed weight in the bunker of poultry house of the chicken breeding workshop "Vitkonproduct" JLLC (Delphi);
   - supervising the development and implementation of software for automating the collection and storage of temperature data in production facilities from WellPro Modbus controllers in the poultry shop "Vitkonproduct" JLLC;
   - supervising the development and implementation of software for automating product weighing and printing barcodes on labels in the poultry workshop of "Vitkonproduct" JLLC;
   - supervising the development and implementation of software for automating product weighing in the "Tolochin Butter and Cheese Factory" OJSC;
