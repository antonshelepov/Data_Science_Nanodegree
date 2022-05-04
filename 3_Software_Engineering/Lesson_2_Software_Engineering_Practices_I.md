## Clean and Modular Code
### Defs
* *Production code*: Software running on production servers to handle live users and data of the intended audience. Note that this is different from production-quality code, which describes code that meets expectations for production in reliability, efficiency, and other aspects. Ideally, all code in production meets these expectations, but this is not always the case.
* *Clean code*: Code that is readable, simple, and concise. Clean production-quality code is crucial for collaboration and maintainability in software development.
* *Modular code*: Code that is logically broken up into functions and modules. Modular production-quality code that makes your code more organized, efficient, and reusable.
* *Module*: A file. Modules allow code to be reused by encapsulating them into files that can be imported into other files.
### Quiz (Clean and Modular Code)
![clean code](/screenshots/cleanAndModular.png "Clean and Modular Code")
![clean codeII](/screenshots/cleanAndModularII.png "Clean and Modular Code")
## Refactoring Code
### Defs
* *Refactoring*: Restructuring your code to improve its internal structure without changing its external functionality. This gives you a chance to clean and modularize your program after you've got it working.
* Since it isn't easy to write your best code while you're still trying to just get it working, allocating time to do this is essential to producing high-quality code. Despite the initial time and effort required, this really pays off by speeding up your development time in the long run.
* You become a much stronger programmer when you're constantly looking to improve your code. The more you refactor, the easier it will be to structure and write good code the first time.
## Writing Clean Code
Use meaningful names.
* *Be descriptive and imply type*: For booleans, you can prefix with ```is_``` or ```has_``` to make it clear it is a condition. You can also use parts of speech to imply types, like using verbs for functions and nouns for variables.
* *Be consistent but clearly differentiate*: ```age_list``` and ```age``` is easier to differentiate than ```ages``` and ```age```.
* *Avoid abbreviations and single letters*: You can determine when to make these exceptions based on the audience for your code. If you work with other data scientists, certain variables may be common knowledge. While if you work with full stack engineers, it might be necessary to provide more descriptive names in these cases as well. (Exceptions include counters and common math variables.)
* *Long names aren't the same as descriptive names*: You should be descriptive, but only with relevant information. For example, good function names describe what they do well without including details about implementation or highly specific uses.
