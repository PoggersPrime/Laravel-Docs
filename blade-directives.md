**Laravel Blade Directives Cheat Sheet**

# @extends('layout')

- Specifies the master layout that the current view should extend.
- Allows you to inherit the structure of a master layout in your view.

# @section('name')

- Defines a section within a view or master layout.
- Content within this section can be filled or extended by child views.

# @yield('name')

- Indicates where the content of a named section should be injected.
- Used in master layouts to specify where child views should inject their content.

# @show

- Specifies that the content of the current section should be displayed.
- Used within a master layout to show the content of a section defined in child views.

# @include('view')

- Includes another Blade view within the current view.
- Useful for reusing common view components across multiple views.

# @inject('variable', 'Class')

- Binds a class instance to a variable name for use within the view.
- Allows you to inject dependencies or services directly into your views.

# @if(condition)

- Conditionally includes content based on a specified condition.
- Allows you to control the flow of content within your Blade templates.

# @elseif(condition)

- Specifies an alternative condition to check if the preceding @if condition is false.
- Allows for multiple conditional branches within an @if block.

# @else

- Specifies an alternative content block to display if the preceding @if condition evaluates to false.
- Provides a way to define alternative content when a condition isn't met.

# @unless(condition)

- Opposite of @if. Displays content only if the specified condition is false.
- Useful for expressing conditions in a more readable way.

# @isset($variable)

- Checks if a variable is set and is not null.
- Allows for conditional rendering based on the existence of a variable.

# @empty

- Indicates content to be displayed if a given variable or array is empty.
- Provides a convenient way to handle empty data sets in your views.

# @switch(variable)

- Provides a way to conditionally execute code blocks based on the value of a variable.
- Alternative to multiple nested if-else statements for cleaner code.

# @case(value)

- Specifies a case within a @switch block that matches a particular value.
- Code block associated with the matching case will be executed.

# @default

- Specifies a default case within a @switch block.
- Code block within @default will be executed if none of the cases match the variable's value.

# @for($i = 0; $i < $count; $i++)

- Creates a for loop that iterates a specified number of times.
- Allows for repeated execution of a code block based on a counter variable.

# @foreach($array as $item)

- Iterates over each item in an array and executes the contained code block for each item.
- Useful for displaying lists or iterating through collections of data.

# @forelse($array as $item)

- Similar to @foreach, but provides a fallback if the array is empty.
- Allows you to specify content to be displayed when the array is empty.

# @while(condition)

- Creates a while loop that continues executing as long as the specified condition is true.
- Useful for repeated execution of a code block based on a dynamic condition.

# @php

- Allows you to write PHP code directly within your Blade template.
- Useful for executing PHP logic inline with your HTML markup.

# @endphp

- Marks the end of a @php code block.
- Indicates that subsequent content is regular Blade markup.

# @verbatim

- Treats the enclosed content as raw, unprocessed text.
- Useful for displaying code examples or snippets without Blade processing.

# @csrf

- Generates a hidden CSRF token field for use in forms.
- Helps protect your application from cross-site request forgery (CSRF) attacks.

# @method('PUT')

- Generates a hidden input field specifying the HTTP method for a form.
- Used to override the default POST method for forms, allowing PUT, PATCH, or DELETE methods.

# @json($array)

- Converts an array or object to JSON format.
- Useful for outputting JSON data directly within your Blade templates.

# @auth

- Displays content only if the user is authenticated.
- Provides a way to conditionally show content based on user authentication status.

# @guest

- Displays content only if the user is a guest (not authenticated).
- Useful for displaying login or registration forms to non-authenticated users.

# @can('permission')

- Displays content only if the current user has the specified permission.
- Allows you to conditionally render content based on user permissions.

# @cannot('permission')

- Displays content only if the current user does not have the specified permission.
- Useful for showing alternative content to users who lack certain permissions.

# @hasSection('name')

- Checks if a named section has been defined in the current view.
- Allows for conditional rendering based on the existence of a section.

# @stack('name')

- Pushes content onto a named stack for use in master layouts.
- Useful for injecting dynamic content into predefined sections of your layout.

# @push('name')

- Pushes content onto a named stack for use in master layouts.
- Content will be appended to any existing content in the specified stack.

# @prepend('name')

- Prepends content onto a named stack for use in master layouts.
- Content will be inserted before any existing content in the specified stack.
