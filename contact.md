---
layout: page
title: Contact-Me
permalink: /Contact/
---
<html lang="en">

I work with data science methods to provide analytics and visualizations on financial and economic information,
real estate, and supply chain. I'm mainly interested in exploring producer prices, inflation, business cycles, financial
markets using a combination of tools: Excel, Python, SQL and Tableau to provide statistics and visualizations.
I have a couple of projects (agricultural commodity market price control using AI and creating a data lake) that I would
like to start making progress on.
<br />
  
If you are interested in sharing ideas and working together, please fill out the form and I'll get back to you right away!
<br />

{
-components: [
- {
input: true,
tableView: true,
inputType: "text",
inputMask: "",
label: "First Name",
key: "firstName",
placeholder: "Enter your first name",
prefix: "",
suffix: "",
multiple: false,
defaultValue: "",
protected: false,
unique: false,
persistent: true,
-validate: {
required: false,
minLength: "",
maxLength: "",
pattern: "",
custom: "",
customPrivate: false
},
-conditional: {
show: "",
when: null,
eq: ""
},
type: "textfield",
$$hashKey: "object:18",
autofocus: false,
hidden: false,
clearOnHide: true,
spellcheck: true,
labelPosition: "top",
inputFormat: "plain",
-tags: [
],
-properties: {
},
hideLabel: true
},
- {
input: true,
tableView: true,
inputType: "text",
inputMask: "",
label: "lastName",
key: "lastName",
placeholder: "Enter your last name",
prefix: "",
suffix: "",
multiple: false,
defaultValue: "",
protected: false,
unique: false,
persistent: true,
-validate: {
required: false,
minLength: "",
maxLength: "",
pattern: "",
custom: "",
customPrivate: false
},
-conditional: {
show: "",
when: null,
eq: ""
},
type: "textfield",
$$hashKey: "object:19",
autofocus: false,
hidden: false,
clearOnHide: true,
spellcheck: true,
labelPosition: "top",
inputFormat: "plain",
-tags: [
],
-properties: {
},
hideLabel: true
},
- {
type: "select",
-validate: {
required: false
},
clearOnHide: true,
persistent: true,
unique: false,
protected: false,
multiple: true,
template: "<span>{{ item.label }}</span>",
authenticate: false,
filter: "",
refreshOn: "",
defaultValue: "",
valueProperty: "",
dataSrc: "values",
-data: {
custom: "",
resource: "",
url: "",
json: "",
-values: [
- {
label: "Raindrops on roses",
value: "raindropsOnRoses",
$$hashKey: "object:215"
},
- {
label: "Whiskers on Kittens",
value: "whiskersOnKittens",
$$hashKey: "object:216"
},
- {
label: "Bright copper kettles",
value: "brightCopperKettles",
$$hashKey: "object:217"
},
- {
label: "Warm woolen Mittens",
value: "warmWoolenMittens",
$$hashKey: "object:218"
},
- [
]
]
},
placeholder: "Select a few",
key: "favoriteThings",
label: "Favorite Things",
tableView: true,
input: true,
$$hashKey: "object:20",
autofocus: false,
hidden: false
},
- {
input: true,
tableView: true,
label: "Message",
key: "message",
placeholder: "Enter your text",
prefix: "",
suffix: "",
rows: 4,
multiple: false,
defaultValue: "",
protected: false,
persistent: true,
-validate: {
required: false,
minLength: "",
maxLength: "",
pattern: "",
custom: ""
},
type: "textarea",
-conditional: {
show: "",
when: null,
eq: ""
},
$$hashKey: "object:21",
autofocus: false,
hidden: false,
wysiwyg: false,
clearOnHide: true,
spellcheck: true,
labelPosition: "top",
inputFormat: "plain",
-tags: [
],
-properties: {
}
},
- {
type: "button",
theme: "primary",
disableOnInvalid: true,
action: "submit",
block: false,
rightIcon: "",
leftIcon: "",
size: "md",
key: "submit",
tableView: false,
label: "Submit",
input: true,
$$hashKey: "object:22",
autofocus: false
}
],
display: "form",
page: 0
}

<iframe src="https://docs.google.com/forms/d/e/1FAIpQLScwvX_F7xEhD3hq3rT9qF_B0_E8LAsREGq7IQ44h0mbFW7hkw/viewform?embedded=true" width="640" height="891" frameborder="0" marginheight="0" marginwidth="0">Loading...</iframe>
</html>
