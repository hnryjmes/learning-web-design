# Learning Web Design

*5th Edition, by Jennifer Niederst Robbins*

`Notes by Henry Cooksley`

### Foreword

### Preface

"Learning Web Design, Fifth Edition, is divided into five parts, each dealing with an important aspect of web development."

"I start off with some important general information about the web design environment, including the various roles you might play, the technologies you might learn, and tools that are available to you."

"We'll cover the markup for text, links, images, forms, and embedded media."

"It provides an introduction to Responsive Web Design, as well as the tools and techniques that are part of the modern developer's workflow."

"You'll get to know some ways that JavaScript is used (including DOM scripting) and existing JavaScript tools such as polyfills and libraries that let you put JavaScript to use quickly, even if you aren't quite ready to write your own code from scratch."

"It also includes a chapter on SVG graphics, which offer great advantages for responsive and interaction design."

## 1 Getting started

### 1 Getting started in web design

Where do I start?

It takes a village (website creation roles)

Content Wrangling

"Anyone who used the title “web designer” needs to be aware that everything we do supports the process of getting the content, message, or functionality to our users."

Information architecture

Content strategy

All Manner of Design

User Experience, Interaction, and User Interface design

"The User Experience designer takes a holistic view of the design process - ensuring the entire experience with the site is favorable."

"UX design is based on a solid understanding of users and their needs based on observations and interviews."

User research and testing reports

"Site designs often begin with user research, including interviews and observations, in order to gain a better understanding of how the site can solve problems or how it will be used."

Wireframe diagrams

"The purpose of a wireframe diagram is to indicate how the screen real estate is divided and where functionality and content such as navigation, search boxes, form elements, and so on, are placed."

"Colors, fonts, and other visual identity elements are deliberately omitted so as not to distract from the structure of the page."

Site diagram

Storyboards and user flow charts

"A storyboard traces the path through a site of application from the point of view of a typical user (a persona in UX lingo)."

Visual (graphic) design

Do Designers Need to Learn to Code?

Code Slinging

Frontend development

Authoring/markup (HTML)

Styling (CSS)

JavaScript and DOM scripting

Backend development

Full-Stack Developers and Unicorns

Other Roles

Product manager

Project manager

SEO specialist

Multimedia producers

(Soft) Skills Every Web Designer Needs

Gearing up for web design

Equipment

Web Production Software

Coding tools

User interface and layout tools

Web graphic creation tools

A variety of browsers

File management and transfer tools

What you've learned

Test yourself

### 2 How the web works

The internet versus the web

A Brief History of the Web

Serving up your information

A word about browsers

Browser Rendering Engines

Web page addresses (URLs)

The Parts of a URL

Simplified URLs

Skipping the protocol

Pointing to default files

The anatomy of a web page

HTML Documents

A Quick Introduction to HTML Markup

Where Are the Pictures?

Adding a Little Style

Adding Behaviors with JavaScript

Putting it all together

### 3 Some big concepts you need to know

A multitude of devices

Mobile Web?

Sticking with the standards

Progressive enhancement

"When designing with progressive enhancement, you start with a baseline experience that makes the content or core functionality available to even the most rudimentary browsers or assistive devices."

Authoring strategy

"When an HTML document is written in logical order and its elements are marked up in a meaningful way, it will be usable on the widest range of browsing environments, including the oldest browsers, future browsers, and mobile and assistive devices."

Styling strategy

Scripting strategy

Responsive web design

M-dot Sites

One web for all (accessibility)

Vision impairment

Mobility impairment

Auditory impairment

Cognitive impairment

US Government Accessibility Requirements: Section 508

The need for speed (site performance)

## 2 HTML for structure

### 4 Creating a simple page (HTML overview)

A web page, step-by-step

Launch a text editor

Creating a New Document in Notepad (Windows)

Creating a New Document in TextEdit (macOS)

Step 1: Start with content

Naming Conventions

Learning from Step 1

Step 2: Give the HTML document structure

The Anatomy of an HTML Element

Basic Document Structure

Introducing Unicode

Step 3: Identify text elements

Mark It Up Semantically

"Your job when marking up content is to choose the HTML element that provides the most meaningful description of the content at hand."

Block and Inline Elements

Default Styles

Step 4: Add an image

Empty Elements

Attributes

Step 5: Change the look with a style sheet

When good pages go bad

Validating your documents

### 5 Marking up text

Paragraphs

Headings

Thematic breaks (horizontal rule)

Lists

Unordered Lists

Ordered Lists

Description Lists

More content elements

Long Quotations

Preformatted Text

Figures

Organizing page content

HTML5 Support in Internet Explorer

Main Content

Headers and Footers

Headers

Footers

Sections and Articles

Aside (Sidebars)

Navigation

Addresses

Document Outlines

The inline element roundup

Text-Level (Inline) Elements

Nesting Elements

Adding Breaks

Accommodating Non-Western Languages

Generic elements (div and span)

Divide It Up with a div

Define a Phrase with span

id and class Attributes

Identify and Classify All Elements

Improving accessibility with ARIA

Roles

Structured Data in a Nutshell

States and Properties

Character escapes

When to Escape Characters

### 6 Adding links

The href attribute

Absolute URLs

Relative URLs

Linking to pages on the web

Linking within your own site

Linking Within a Directory

Linking to a Lower Directory

Linking to a Higher Directory

Linking with Site Root Relative Pathnames

Writing Pathnames to Images

Linking to a Specific Point in a Page

Linking to a Fragment in Another Document

Targeting a new browser window

Pop-up Windows

Mail links

Telephone links

### 7 Adding images

First, a word on image formats

The img element

Providing the Location with src

Take Advantage of Caching

Providing Alternative Text with alt

Providing the Dimensions with width and height

"These attributes have become less useful in the age of modern web development."

"They should never be used to resize an image (use your image-editing program or CSS for that), and they should be omitted entirely when you're using one of the responsive image techniques introduced later in this chapter."

Adding SVG images

Embedded with the img Element

Inline in the HTML Source

Embedded with the object Element

Used as a Background Image with CSS

SVG Fallbacks

Responsive image markup

How It Works

"In short, responsive images work this way: you provide multiple images, sized or cropped for different screen sizes, and the browser picks the most appropriate one based on what it knows about the current viewing environment."

High-Density Displays (x-descriptor)

"Reference pixels are also known as points (PT) in iOS, Device Independent Pixels (DP or DiP) in Android, or CSS pixels because they are the unit of measurement we use in style sheets."

Variable-Width Images (w-descriptor)

Art Direction (picture element)

"The srcset attribute supplies the URL for the image to use if the media query is a match."

Alternative Image Formats (type Attribute)

Browser Support

Responsive Images Summary

### 8 Table markup

How to use tables

Minimal table structure

Table headers

Spanning cells

Column Spans

Row Spans

Space in and Between Cells

Table Accessibility

Describing Table Content

Connecting Cells and Headers

Row and column groups

Row Group Elements

Column Group Elements

Wrapping up tables

### 9 Forms

How forms work

From Data Entry to Response

A Word About Encoding

The form element

The action Attribute

The method Attribute

Variables and content

The name Attribute

Naming Your Variables

The great form control roundup

Text-Entry Controls

disabled and readonly

Specialized Text-Entry Fields

Drop-Down Suggestions

Submit and Reset Buttons

Radio and Checkbox Buttons

Menus

File Selection Control

Hidden Controls

Date and Time Controls

"HTML5 introduced six new input types that make date and time selection widgets part of a browser's standard built-in display capabilities, just as they can display checkboxes, pop-up menus, and other widgets today."

Numerical Inputs

Color Selector

A Few More Form Elements

Form accessibility features

Labels

fieldset and legend

DIY Form Widgets

Form layout and design

Usable Forms

Avoid unnecessary questions.

Consider the impact of label placement.

Choose input types carefully.

Group related inputs.

Clarify primary and secondary actions.

Styling Forms

### 10 Embedded media