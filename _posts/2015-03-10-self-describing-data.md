---
layout: post
title: Self-Describing Data
---

When I have to display data on a page, I like to follow the age-old storytelling advice of “show, don’t tell.” That is to say, rather than “tell” you about the data you’re viewing, I’ll simply “show” it you. It’s up to you to read between the lines, draw conclusions, and pick up what I’m throwing down.

I also like to remove everything that isn’t totally necessary; often times it’s the metadata—the data about the data—that isn’t always necessary to show on your page.

An example of unnecessary metadata is when you’re showing the labels of the properties of an object whereby the property type can be deduced from its value. This clutters things even worse when there are many object instances on the page.

Let’s say that we’re dealing with various objects of different types. I’m going to give you the value of some properties and you tell me what properties might be. Take a wild guess:

<table class="table">
<tr><td>somthingsomething@example.com</td></tr>
<tr><td>127.0.0.1</td></tr>
<tr><td>http://nngroup.com</td></tr>
<tr><td>Joseph Doe</td></tr>
<tr><td>742 Evergreen Terrace</td></tr>
<tr><td>36°59′56.3″N 109°02′42.6″W</td></tr>
<tr><td>339-23-2303</td></tr>
<tr><td>(415) 555-3458</td></tr>
<tr><td>71° F</td></tr>
<tr><td>December 7, 1941</td></tr>
<tr><td>215 lbs.</td></tr>
</table>

I should hope that you determined these to be the following:

<table class="table">
<tr><th>Email Address</th><td>somthingsomething@example.com</td></tr>
<tr><th>IP Address</th><td>127.0.0.1</td></tr>
<tr><th>URL</th><td>http://nngroup.com</td></tr>
<tr><th>A Person’s Name</th><td>Joseph Doe</td></tr>
<tr><th>Street Address</th><td>742 Evergreen Terrace</td></tr>
<tr><th>Longitude &amp; Latitude</th><td>36°59′56.3″N 109°02′42.6″W</td></tr>
<tr><th>Social Security Number</th><td>339-23-2303</td></tr>
<tr><th>Phone Number</th><td>(415) 555-3458</td></tr>
<tr><th>Temperature</th><td>71° F</td></tr>
<tr><th>Date</th><td>December 7, 1941</td></tr>
<tr><th>Weight</th><td>215 lbs.</td></tr>
</table>

Now, not everyone would be able to recognize an IP address but I’d wager if you can’t recognize an IP address you probably don’t know what one is anyways. The only downside of not including the label is that you have no way of learning what you don’t know.

It is also interesting to note that a lot of the numerical data is only recognizable due to its formatting, whether it uses hyphens, spaces, degrees, periods, primes, parentheses or units of measurement. Without these cues it would be much more difficult to distinguish what the numerical data represents. You could even think of this formatting as a label, too, it’s just lighter weight.

Numbers with only space or hyphen formatting can be pretty ambiguous. I would argue that a social security number looks very similar to a phone number or any other type of number for that matter and would therefore require an explicit label.

In the case of temperature and weight, it’s the units of measurement that inform what the data measures. I don’t need to tell you that lbs. are for weight and degrees Fahrenheit measures temperature.

Given that some data, along with its formatting, supplies the reader with enough context to distinguish what type of property it is, consider leaving it off your pages in order to free up space and tell a better story.
