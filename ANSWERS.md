## Questions

What does the second 'nil' argument in the line 6 text_field_tag of teachers/new.html.erb represent?

It represents the default value of the parameter.

Go to `localhost:3000/teachers` in your browser; why does this not work?

It doesn't work because there is no get '/teachers/' route and the browser just performed a GET request.

What type of request did your browser just perform?

A POST request.

Go back to `localhost:3000/teachers/new`; submit the form again. What URL do you end up at?

`localhost:3000/teachers`

Why does `localhost:3000/teachers` work now?

It works because my browser performed a POST request, not a GET request to get to that url which we have a route for.
