# Live-Project
Working on C# live project was one of most rewarding challenges I have taken part in. I got to add contribution in building an MVC application. I learned how to expand my thought process and look at the bigger picture. I also got a much better understanding of how to just go in headfirst and start doing what I know how to do, rather than worry about the concepts that I do not. It made me gain confidence working on my own smaller piece of the project and learn on the job the importance of working as a team. During the course of the two weeks, I was able to complete multiple stories, including front end stories, bug fixing, and back-end stories. 
Below are code snippets and description of the stories.

#Debugging Story
The Donation Button when I started the story was not working, my task was to create a new view and from there create a form. 
<!DOCTYPE html>
<body>
    @using (Html.BeginForm("Donate", "Home", FormMethod.Post))
    {
    <div class="form-group col-12" >
        <div class="donate-form">
            <label class="donate-label">Name&#8727;</label>
            <input class="donate-name" type="text" placeholder="First Name" />
            <input class="donate-name" type="text" placeholder="Last Name" />
        </div>
        <div class="donate-form">
            <label class="donate-label">Email Address&#8727;</label>
            <input class="donate-input" type="text" placeholder="Email Address" />
        </div>
        <div class="donate-form">
            <label class="donate-label">Address</label>
            <input class="donate-input" type="text" placeholder="Address" />
        </div>
        <div class="donate-form">
            <label class="donate-label">Donation Amount($)&#8727;</label>
            <input class="donate-input" type="text" placeholder="Donation Amount" />
        </div>
        <div class="donate-form">
            <label class="donate-label">Donation Comments</label>
            <input class="donate-input" type="text" input style="height:100px;font-size:8pt " placeholder="Place comments here..." />
        </div>
            <button type="submit" class="btn btn-light ">Submit</button>
        </div>
        }
</body>
</html>


#Back-End Stories


