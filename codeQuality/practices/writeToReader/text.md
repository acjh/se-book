<link rel="stylesheet" href="{{baseUrl}}/css/textbook.css">

<div class="website-content">

<div id="title">

#### Write to the Reader

</div>

<div id="body">

Do not write comments as if they are private notes to self. Instead, write them well enough to be understood by another programmer. One type of comments that is almost always useful is the _header comment_ that you write for a class or an operation to explain its purpose.

![][Bad] %%Reason: this comment will only make sense to the person who wrote it%%
```java
// a quick trim function used to fix bug I detected overnight
void trimInput(){
    ....
}
```

![][Good]
```java
/** Trims the input of leading and trailing spaces */
void trimInput(){
    ....
}
```

[Bad]: {{baseUrl}}/images/Bad.png "Bad"
[Good]: {{baseUrl}}/images/Good.png "Good"

</div>

</div>
