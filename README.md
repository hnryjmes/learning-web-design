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

Window-in-a-window (iframe)

Multipurpose embedder (object)

Farewell Flash

Video and audio

The Good News and the Bad News

How Media Formats Work

Server Setup

Adding Video to a Page

Video and Audio Encoding Tools

Flash Video Fallback

Adding Audio to a Page

Adding Text Tracks

Canvas

The canvas Element

Drawing with JavaScript

## 3 CSS for presentation

### 11 Introducing Cascading Style Sheets

The benefits of CSS

The Power of CSS

How style sheets work

The big concepts

Inheritance

Conflicting Styles: The Cascade

Assigning Importance

"Within a style sheet, if there are conflicts within style rules of identical weight, whichever one comes last in the list “wins.”"

The Box Model

Grouped Selectors

CSS units of measurement

CSS Units

Absolute Units

Relative Units

Developer tools right in your browser

Moving forward with CSS

### 12 Formatting text

Basic font properties

A Word About Property Listings

Specifying the Font Name

Say Hello to Web Fonts

Specifying Font Size

"I'm going to cut to the chase and tell you that, despite all these options, the preferred values for font-size in contemporary web design are the relative length units em and rem, as well as percentage values."

Font Weight (Boldness)

Font Style (Italics)

Font Variant in CSS2.1 (Small Caps)

Font Stretch (Condensed and Extended)

The Shortcut font Property

Advanced typography with CSS3

Font Variant in CSS3

Other CSS3 Properties

Changing text color

A few more selector types

Descendant Selectors

ID Selectors

Other Contextual Selectors

Class Selectors

Specificity 101

The Universal Selector

Text line adjustments

Line Height

Indents

Horizontal Text Alignment

Underlines and other “decorations”

Changing capitalization

Spaced out

Text shadow

The Other Text Properties

Changing list bullets and numbers

Choosing a Marker

Marker Position

Make Your Own Bullets

### 13 Colors and backgrounds

Specifying color values

Color Names

RGB Color Values

RGBa Color

HSL Color

Summing Up Color Values

Foreground color

Background color

Clipping the background

Playing with opacity

Pseudo-class selectors

Link Pseudo-Classes

User Action Pseudo-Classes

Hover on Touch Devices

Other Pseudo-Class Selectors

More CSS3 Pseudo-Classes

Pseudo-Element Selectors

First Letter and Line

Generated Content with ::before and ::after

Attribute selectors

Background images

Adding a Background Image

Background Repeating

Background Position

Background Position Origin

Background Attachment

Background Size

The shorthand background property

Multiple Backgrounds

Like a rainbow (gradients)

Linear Gradients

Radial Gradients

Repeating Gradients

Browser Support and Vendor Prefixes

Vendor Prefixes

Designing Gradients

Using the link Element

Importing with @import

Using Modular Style Sheets

### 14 Thinking inside the box

The element box

Specifying box dimensions

Sizing the Content Box

Using the border-box Model

"In fact, many developers simply set everything in the document to use the border-box model by setting it on the root (html) element, then setting all other elements to inherit, like this: 
html {box-sizing: border-box;}
*, *:before, *:after {box-sizing: inherit;}"

Specifying Height

Handling Overflow

Padding

The Shorthand padding Property

Borders

Border Style

Border Width (Thickness)

Border Color

CSS Outlines

Combining Style, Width, and Color

Rounded Corners with border-radius

Picture-Perfect Borders

Margins

Margin Behavior

Assigning Display Types

Box drop shadows

### 15 Floating and positioning

Normal flow

Floating

Floating Inline and Block elements

Clearing Floated Elements

Floating Multiple Elements

Containing Floats

Fancy text wrap with CSS shapes

Using a Transparent Image

Using a Path

CSS Shapes Resources

Positioning basics

Types of Positioning

Specifying Position

Relative positioning

Absolute positioning

Containing Blocks

Specifying Position

Stacking Order

### 16 CSS layout with flexbox and grid

Flexible boxes with CSS flexbox

"The defining aspect of flex layout is the ability to make the flex items “flex,” altering their width/height to fill the available space in the main dimension."

Multicolumn Layout

Setting Up a Flexbox Container

Flexbox Resources

Controlling the “Flow” Within the Container

Controlling the Alignment of Flex Items in the Container

Determining How Items “Flex” in the Container

Absolute Versus Relative Flex

Changing the Order of Flex Items

Browser Support for Flexbox

CSS grid layout

The Obligatory Talk About Browser Support

How Grid Layout Works

Grid Terminology

Declaring Grid Display

Setting Up the Grid

Placing Grid Items

Implicit Grid Behavior

Spacing and Alignment

Online Grid Resources

### 17 Responsive web design

Why RWD?

The responsive recipe

Setting the Viewport

Flexible Grids (Fluid Layouts)

Making Images Flexible

Media Query Magic

Choosing breakpoints

Module-Based Breakpoints

Em-Based Breakpoints

How Wide Is the Viewport?

Designing responsively

Content Hierarchy

Layout

Typography

Navigation

Images

Special Content

The Trouble with Tables

A few words about testing

Real Devices

Emulators

Third-Party Services

More RWD resources

### 18 Transitions, transforms, and animation

Ease-y does it (CSS transitions)

Transition Basics

Timing Functions

Setting a Delay

The Shorthand transition Property

Applying Multiple Transitions

A Transition for All Occasions

CSS transforms

Transforming the Angle (rotate)

Transforming the Position (translate)

Transforming the Size (scale)

Making It Slanty (skew)

Applying Multiple Transforms

Smooth Transforms

3-D Transforms

Keyframe animation

Establishing the Keyframes

Adding Animation Properties

When to Use Keyframe Animation

Animation Inspectors

### 19 More CSS techniques

Styling forms

Styling tables

Separated Borders

Collapsed Borders

Table Layout

Table Display Properties

A clean slate (reset and Normalize.css)

CSS Reset

Normalize.css

Image replacement techniques

CSS sprites

CSS feature detection

CSS Feature Queries (@supports)

Modernizr

### 20 Modern web development tools

Getting cozy with the command line

The Command-Line Terminal

Getting Started with Commands

Learning More

CSS power tools (processors)

Introduction to Preprocessors (Especially Sass)

Introduction to Postprocessors (Mostly PostCSS)

Build tools (Grunt and Gulp)

Automation

Some Common Tasks

Grunt and Gulp

Building Sites with Data and Templates

Version control with Git and GitHub

Why Use Git

How Git Works

Git Tools and Resources

### 4 JavaScript for behavior

### 21 Introduction to JavaScript

What is JavaScript?

What It Isn't

What It Is

What JavaScript Can Do

Adding JavaScript to a page

Embedded Script

External Scripts

Script Placement

The anatomy of a script

The Basics

Variables

Comparison Operators

if/else statements

Loops

Functions

Variable Scope and the var Keyword

Events

As an HTML Attribute

As a Method

addEventListener

### 22 Using JavaScript and the Document Object Model

Meet the DOM

The Node Tree

Accessing DOM Nodes

Manipulating Nodes

Adding and Removing Elements

Polyfills

"A shim that mimics a future API providing fallback functionality to older browsers."

HTML5 shim (or shiv)

Selectivizr

Picturefill (A Responsive Image Polyfill)

JavaScript libraries

What Is Ajax?

jQuery and Other Libraries

How to Use jQuery

Scripting with jQuery

But What If I Don't Know How to Write Scripts?

### 5 Web images

#### 23 Web image basics

Image sources

Create Your Own Images

Stock Photography and Illustrations

Clip Art and Icons

Hire a Designer

Meet the formats

The Photogenic JPEG

The Powerful PNG

Common Color Palettes

Ol' Grandpa GIF

The Performant WebP

Choosing the Best Bitmapped Format

Image size and resolution

Image Resolution

Screen Resolution

The Upshot

Image asset strategy

Can It Be Done with CSS?

Can It Be an SVG?

What Is the Best Bitmapped Format?

Does Your Layout Require Responsive Images?

Does Your Site Have a Lot of Images?

Favicons

Old-Fashioned Browser Favicons

Full Favicon Set

Icon Creation

### 24 Image asset production

Saving images in web formats

Working with transparency

How Binary Transparency Works

How Alpha Transparency Works

PNG-8 Alpha Transparency

Making Transparent PNGs and GIFs

Responsive image production tips

Images for Responsive Layouts

Art-Directed Images

Images for High-Density Displays

Viva la Automation!

Image optimization

General Optimization Guidelines

Optimizing JPEGs

“Optimizing” PNG-24

Optimizing PNG-8 and GIF

Optimization Tools

### 25 SVG (Scalable Vector Graphics)

