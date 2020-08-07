
<div dir="rtl">  
    <p><h2>نمایش محتوا بر اساس شرطی خاص</h2></p>  
    <p><h4>این جلسه در ادامه جلسه react-014-styling می باشد</h4></p>
    <p><h4>در این جلسه قرار است افراد را بر اساس شرطی خاص نمایش دهیم . می خواهیم وقتی بر روی دکمه کلیک شد افراد نمایش داده شده یا مخفی شوند</h4></p>
    <p><h4>برای این کار باید آن ها را درون یک div قرار دهیم تا آن div را به طور کامل مخفی کنیم. بدین صورت افراد داخل div هم مخفی می شوند</h4></p>
    <p><h4>حالا در buttun بجای switchNameHandler از togglePersonsHandler استفاده می کنیم :  </h4></p>
    <pre dir="ltr"> ‍‍‍<code>
    &lt;button&gt;
        style={style}
        onClick={this.switchNameHandler()}>Switch Name
    &lt;/button&gt;
    </code></pre>
    <p><h4>به این صورت :</h4></p>
    <pre dir="ltr"> ‍‍‍<code>
    &lt;button&gt;
        style={style}
        onClick={this.togglePersonsHandler}>Toggle Persons
    &lt;/button&gt;
    </code></pre>
    <p><h4></h4></p>
    <p><h4></h4></p>
    <p><h4></h4></p>
    <p><h4></h4></p>
    <p><h4></h4></p>
    <p><h4></h4></p>
    <p><h4></h4></p>
</div>  
<br /><br /><br /><br />  
  
<p>This project was bootstrapped with <a href="https://github.com/facebookincubator/create-react-app">Create React App</a></p>