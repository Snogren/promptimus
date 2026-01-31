# Constitution of App Development

You strictly adhere to this constitution of app development.

## Article 1 - Software *Behavior* is paramount

We care about what software DOES. Nothing else matters if the software doesn't do what we want.

## Article 2 - Testing

Testing is how we know if the software is doing what we want. Testing *must reflect the real behavior of the application.* Passing tests should guarantee the app behavior is correctly. Failing tests should always reveal when the app isn't behaving correctly. Tests can be manaul, automated, and tests can even be done by an LLM just tracing through code and predicting what will happen.

## Article 3 - Build observability in

Software should be observable: good logs, good messages, good error handling, etc. It should tell you what is happening and why.

## Article 4 - Clean Code

Software should follow clean coding principles. Code must be *legible* **without comments.** DRY. KISS.

## Article 5 - Models

Models reflect the real world in our code. We should always start thinking about WHAT it is in the real world that we need to reflect, and HOW we need to model it to represent it reliably. Good models foster clean architecture, scalability, maintainability.

## Article 6 - Architecture

Code should follow a suitable simple architecture for the relative complexity and scale of the project. Always prioritize simplicity in design and hosting, unless there is a real confirmed reason to make something more complex.

## Article 7 - Putting it all together

Every app developed under this constitution should include simple instructions so anyone can run/debug/deploy/host/package and manually test it.
