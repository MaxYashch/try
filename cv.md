**Maksim Yashchykoucki**
---
2. E-mail: maxyashch@gmail.com  
Skype: Maksim Yashchykoucki  
Phone:+375-29-57-86-777  
Telegram:@MaximTovaroved  
LinkedIn : [Maksim Yashchykoucki](http://linkedin.com/in/maksim-yashchikovskiy-8836b817a)
3. I’m doing my best to become an expert Front end Web developer and Build up a career as a programmer.

4. Programming languages: HTML, SCSS/CSS, Javascript
Tools: GIT, Sublime Text, VS Code, Adobe Photoshop

5. Code example
```
var list = document.querySelector('.todo-list'); 
var items = list.children; 
var emptyListMessage = document.querySelector('.empty-tasks');
var newItemForm = document.querySelector('.add-form');
var newItemTitle = newItemForm.querySelector('.add-form-input');
var taskTemplate = document.querySelector('#task-template').content;
var newItemTemplate = taskTemplate.querySelector('.todo-list-item');
var toggleEmptyListMessage = function () {
  if (items.length === 0) {
    emptyListMessage.classList.remove('hidden');
  } else {
    emptyListMessage.classList.add('hidden');
  }  };
var addCheckHandler = function (item) {
  var checkbox = item.querySelector('.todo-list-input');
  checkbox.addEventListener('change', function () {
    item.remove();
    toggleEmptyListMessage();
  });
};
for (var i = 0; i < items.length; i++) {
  addCheckHandler(items[i]);
}
newItemForm.addEventListener('submit', function (evt) {
  evt.preventDefault();
  var taskText = newItemTitle.value;
  var task = newItemTemplate.cloneNode(true);
  var taskDescription = task.querySelector('span');
  taskDescription.textContent = taskText;
  addCheckHandler(task);
  list.appendChild(task);
  toggleEmptyListMessage();
  newItemTitle.value = '';
});
```
6. Expierence
UE "Belmedtekhnika" 2009-2015  
Position: manager  
Ltd “Tabak Invest” 2015-till now  
Position: Operations Specialist of Logistics Department
7. I’ve graduated It-academy-courses “Front-end Development” 2019  
Belarusian State Economic University 2003-2007 Economist
8. I studied at Streamline courses and finished Intermediate level there.
