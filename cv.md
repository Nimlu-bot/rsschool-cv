__Nesterov Sergey__

* Contacts
	* e-mail snesterov@gmail.com
	* telegram SANesterov

* Summary
	* I am cheerful and very responsible person. I can easily adapt to any conditions and I am fast learner. I am interested in everything that surrounds me. I like to communicate with new people, like to read and otherwise develop. 

* Skills
	* Git
	* bash
	* js
	 

* Code examples


	```
	var fs = require('fs');
	let array = [];
	fs.readFile('users.txt', function (err, data) {
	if (err) throw err;
	array = data.toString().split("\r\n");

	for (i in array) {
		fs.appendFile('output.txt', 'New-Item -Path \"f:\\Обмен\\' + array[i] + '\" -ItemType \"directory\" \r\n', function (err) {
		if (err) throw err;
		})s
	}
	})
	```


 *  Experience
	* No experience.

* Education
	* Higher education. Graduated from BSUIR.  

* English
	* A2, no speaking practice since studying at the university. Reading technical literature without problems.