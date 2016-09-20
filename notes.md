
https://validator.w3.org/nu/#textarea


advice from:
----------------------------
http://csswizardry.com/2011/01/create-a-centred-horizontal-navigation/
<ul class="nav">
  <li><a href="/">Home</a></li>
  <li><a href="/about/">About</a></li>
  <li><a href="/work/">Work</a></li>
  <li><a href="/clients/">Clients</a></li>
  <li><a href="/contact/">Contact</a></li>
</ul>

.nav{
    border:1px solid #ccc;
    border-width:1px 0;
    list-style:none;
    margin:0;
    padding:0;
    text-align:center;
}
.nav li{
    display:inline;
}
.nav a{
    display:inline-block;
    padding:10px;
}

----------------------------





# learned that above seems to make displaying of the information funky. Definitely, don't do additional ptag.
# creates a drop down menu called details.
<details>
   <p>Review #1 Title: </p>
  # this one:
   <p>Testing to see if looks better (after p tag - it doesn't)</p>
   <p>Reviewer #1: </p>
   <p>Review #1 Date: </p>
   <p> Review #1: </p>
</details>


<ul style="list-style: none; ul>"

# tried this which is better?

<div>
   <p>Review #1 Title: </p>
   <p>Testing to see if looks better (after p tag - it doesn't)</p>
   <p>Reviewer #1: </p>
   <p>Review #1 Date: </p>
   <p> Review #1: </p>
</div>


-->
    <ul>
      <li>Review #1 Title:</li>
      <li>Reviewer #1:</li>
      <li>Review #1 Date:</li>
      <li>Review #1: </li>
    </ul>

# classes are how you should use id. A bunch of p tags.
id="description"
    #description{
      color: blue;
    }



# learned today:
Warning: Comments seen before doctype. Internet Explorer will go into the quirks mode.

# that when my html isn't working like I think. I should check the following errors:
1. failed
