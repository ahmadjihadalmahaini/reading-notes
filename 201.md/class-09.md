# read09
# Forms :
## The <form> HTML element represents a document section containing interactive controls for submitting information.
## All forms start with a <form> element, like this:

## form action="/my-handling-form-page" method="post"

## form
## 
# ![](https://www.htmlgoodies.com/wp-content/uploads/2021/04/HTML-Forms-From-Basics-to-Style-Layouts-Figure2.gif)
## This element formally defines a form. It's a container element like a <section> or <footer> element, but specifically for containing forms; it also supports some specific attributes to configure the way the form behaves. All of its attributes are optional, but it's standard practice to always set at least the action and method attributes:
## The action attribute defines the location (URL) where the form's collected data should be sent when it is submitted.
## The method attribute defines which HTTP method to send the data with (usually get or post).
## The "label"  "input", and <textarea> elements :
## Our contact form is not complex: the data entry portion contains three text fields, each with a corresponding <label>:

## The input field for the name is a single-line text field.
## The input field for the e-mail is an input of type email: a single-line text field that accepts only e-mail addresses.
## The input field for the message is a <textarea>; a multiline text field.
#  How to collect information from visitors??
## Editor’s Note: This article was originally published by Web Marketing Today. Practical Ecommerce acquired Web Marketing Today in 2012. In 2016, we merged the two sites, leaving Practical Ecommerce as the successor.

## Who are your company’s best online prospects? Probably the people who have already visited your site. How can you continue to market to them? One way, of course, is through an e-mail newsletter. But you can market more directly than that.

## HTML defines the following control types:

## buttons
## Authors may create three types of buttons:
## submit buttons: When activated, a submit button submits a form. A form may contain more than one submit button.
## reset buttons: When activated, a reset button resets all controls to their initial values.
## push buttons: Push buttons have no default behavior. Each push button may have client-side scripts associated with the element's event attributes. When an event occurs (e.g., the user presses the button, releases it, etc.), the associated script is triggered.
## Authors should specify the scripting language of a push button script through a default script declaration (with the META element).

## Authors create buttons with the BUTTON element or the INPUT element. Please consult the definitions of these elements for details about specifying different button types.

## Note. Authors should note that the BUTTON element offers richer rendering capabilities than the INPUT element.

## checkboxes
## Checkboxes (and radio buttons) are on/off switches that may be toggled by the user. A switch is "on" when the control element's checked attribute is set. When a form is submitted, only "on" checkbox controls can become successful.
## Several checkboxes in a form may share the same control name. Thus, for example, checkboxes allow users to select several values for the same property. The INPUT element is used to create a checkbox control.

## radio buttons
## Radio buttons are like checkboxes except that when several share the same control name, they are mutually exclusive: when one is switched "on", all others with the same name are switched "off". The INPUT element is used to create a radio button control.
## If no radio button in a set sharing the same control name is initially "on", user agent behavior for choosing which control is initially "on" is undefined. Note. Since existing implementations handle this case differently, the current specification differs from RFC 1866 ([RFC1866] section 8.1.2.4), which states:
## At all times, exactly one of the radio buttons in a set is checked. If none of the <INPUT> elements of a set of radio buttons specifies `CHECKED', then the user agent must check the first radio button of the set initially.
## Since user agent behavior differs, authors should ensure that in each set of radio buttons that one is initially "on".

## menus
## Menus offer users options from which to choose. The SELECT element creates a menu, in combination with the OPTGROUP and OPTION elements.
## text input
## Authors may create two types of controls that allow users to input text. The INPUT element creates a single-line input control and the TEXTAREA element creates a multi-line input control. In both cases, the input text becomes the control's current value.
## file select
## This control type allows the user to select files so that their contents may be submitted with a form. The INPUT element is used to create a file select control.
## hidden controls
## Authors may create controls that are not rendered but whose values are submitted with a form. Authors generally use this control type to store information between client/server exchanges that would otherwise be lost due to the stateless nature of HTTP (see [RFC2616]). The INPUT element is used to create a hidden control.
## object controls
## Authors may insert generic objects in forms such that associated values are submitted along with other controls. Authors create object controls with the OBJECT element.
## The elements used to create controls generally appear inside a FORM element, but may also appear outside of a FORM element declaration when they are used to build user interfaces. This is discussed in the section on intrinsic events. Note that controls outside a form cannot be successful controls.
# JavaScript Events:
## What can JavaScript Do?
## Event handlers can be used to handle and verify user input, user actions, and browser actions:

## Things that should be done every time a page loads
## Things that should be done when the page is closed
## Action that should be performed when a user clicks a button
## Content that should be verified when a user inputs data And more ...
## Many different methods can be used to let JavaScript work with events:

## HTML event attributes can execute JavaScript code directly
## HTML event attributes can call JavaScript functions
## You can assign your own event handler functions to HTML elements
## You can prevent events from being sent or being handled And more ...


## What are Events in JavaScript?
## Javascript has events that provide a dynamic interface to a webpage. These events are connected to elements in the Document Object Model(DOM).

## Also, these events by default use the bubbling propagation i.e, upwards in the DOM from children to parent. We can bind events either as inline or in an external script. With the help of JavaScript, you can detect when certain events happen, and cause things to occur in response to those events.

## Types of Events in JavaScript
## There are different types of events in JavaScript that are used to react to events. Here, we will discuss some of the famous or most commonly used events such as:

### Onclick
### Onkeyup
###  Onmouseover
### Onload
### Onfocus
# ![](https://res.cloudinary.com/practicaldev/image/fetch/s--J43C-IwA--/c_imagga_scale,f_auto,fl_progressive,h_900,q_auto,w_1600/https://dev-to-uploads.s3.amazonaws.com/i/1zm80qaekzgu8p54w98g.jpg)