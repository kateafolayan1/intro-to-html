								# intro-to-html


HTML is refers to Hypertext Makeup Language wchich to structure a web page you visit. 
Its a completesIt consists of series of element which is used to wrap, enclosed, or make up a different part of contents to make it appear or act in a certain way.


			HTML are made uHTML are made up of two things which are :
Element: 	This are tags which has a text content in side of it
Empty Tags:	This are tags without a text content

NOTE: There are general rules  that follows this two above:
Attributes		<p>This is my page</p>
Element			<!DOCTYPE html> 
			<html lang="en">
   			<head>
Opening Tags		<>
Closing Tags		</>
Text Contents		<hi>Welcome to my My Page</hi>
Enclose Text Contents 	<title>My Note</title>
    			</head>
    			<body>
    			<hi>Welcome to my My Page</hi>
    			<p>This is my page</p>
    			</body>
    			</html>

		EXAMAPLE OF A PROPER ELMENTE & EMPTY TAGS

<!DOCTYPE html> 
<html lang="en">
   <head>
   	  <title>My Note</title>
    </head>
    <body>
    	<hi>Welcome to my My Page</hi>
    	<p>This is my page</p>
    </body>
    	
</html>

HTML (Hypertext Markup Language) elements historically were categorized as either "block-level" elements or "inline-level" elements. Since this is a presentational characteristic it is nowadays specified by CSS in the Flow Layout.

Inline elements are those which only occupy the space bounded by the tags defining the element, instead of breaking the flow of the content.

Inline

Let's look at the following example which demonstrates an inline element:

<div>The following span is an <span class="highlight">inline element</span>;
its background has been colored to display both the beginning and end of
the inline element's influence.</div>

	LIST OF "INLINE" ELEMENT

The following elements are inline by default (although block and inline elements are no longer defined in HTML 5, use content categories instead):

    	1.	<a>: The Anchor element

The <a> HTML element (or anchor element), with its href attribute, creates a hyperlink to web pages, files, email addresses, locations in the same page, or anything else a URL can address.

Content within each <a> should indicate the link's destination. If the href attribute is present, pressing the enter key while focused on the <a> element will activate it.

	EXAMPLES
<p>You can reach Michael at:</p>

<ul>
  <li><a href="https://afolayantobi84@yahoo.com">Website</a></li>
  <li><a href="mailto:m.olaketurah@gmail.com">Email</a></li>
  <li><a href="tel:+2347088869829">Phone</a></li>
</ul>

	OUTCOME
You can reach Kate at:

    Website
    Email
    Phone



    	2.	<abbr>: The Abbreviation element

The <abbr> HTML element represents an abbreviation or acronym; the optional title attribute can provide an expansion or description for the abbreviation. If present, title must contain this full description and nothing else.
    
	EXAMLES
<p>You can use <abbr title="Cascading Style Sheets">CSS</abbr> to style your <abbr title="HyperText Markup Language">HTML</abbr>.</p>

	OUTCOME
You can use CSS to style your HTML.


	3.	The <acronym> HTML element allows authors to clearly indicate a sequence of characters that compose an acronym or abbreviation for a word.

Warning: Don't use this element. Use the <abbr> element instead.

	EXAMPLE
<p>The <acronym title="World Wide Web">WWW</acronym> is only a component of the Internet.</p>


    	4. 	<audio>: The Embed Audio element

The <audio> HTML element is used to embed sound content in documents. It may contain one or more audio sources, represented using the src attribute or the <source> element: the browser will choose the most suitable one. It can also be the destination for streamed media, using a MediaStream.
	
	EXAMPLE
<figure>
    <figcaption>Listen to the T-Rex:</figcaption>
    <audio
        controls
        src="/media/cc0-audio/t-rex-roar.mp3">
            Your browser does not support the
            <code>audio</code> element.
    </audio>
</figure>


    	5.	<b>: The Bring Attention To element

The <b> HTML element is used to draw the reader's attention to the element's contents, which are not otherwise granted special importance. This was formerly known as the Boldface element, and most browsers still draw the text in boldface. However, you should not use <b> for styling text; instead, you should use the CSS font-weight property to create boldface text, or the <strong> element to indicate that text is of special importance.

	EXAMPLE
<p>The two most popular science courses offered by the school are <b class="term">chemistry</b> (the study of chemicals and the composition of substances) and <b class="term">physics</b> (the study of the nature and properties of matter and energy).</p>

	OUCOME
The two most popular science courses offered by the school are chemistry (the study of chemicals and the composition of substances) and physics (the study of the nature and properties of matter and energy).


    	6. 	<bdi>: The Bidirectional Isolate element

The <bdi> HTML element tells the browser's bidirectional algorithm to treat the text it contains in isolation from its surrounding text. It's particularly useful when a website dynamically inserts some text and doesn't know the directionality of the text being inserted.

	EXAMPLE
<h1>World wrestling championships</h1>

<ul>
   <li><bdi class="name">Evil Steven</bdi>: 1st place</li>
   <li><bdi class="name">François fatale</bdi>: 2nd place</li>
   <li><span class="name">تیز سمی</span>: 3rd place</li>
   <li><bdi class="name">الرجل القوي إيان</bdi>: 4th place</li>
   <li><span class="name" dir="auto">تیز سمی</span>: 5th place</li>
</ul>

	OUTCOME
World wrestling championships

    Evil Steven: 1st place
    François fatale: 2nd place
    تیز سمی: 3rd place
    الرجل القوي إيان: 4th place
    تیز سمی: 5th place


    	7. 	<bdo>: The Bidirectional Text Override element

The <bdo> HTML element overrides the current directionality of text, so that the text within is rendered in a different direction.

	EXAMPLE
<h1>Famous seaside songs</h1>

<p>The English song "Oh I do like to be beside the seaside"</p>

<p>Looks like this in Hebrew: <span dir="rtl">אה, אני אוהב להיות ליד חוף הים</span></p>

<p>In the computer's memory, this is stored as <bdo dir="ltr">אה, אני אוהב להיות ליד חוף הים</bdo></p>

	OUTCOME
Famous seaside songs

The English song "Oh I do like to be beside the seaside"

Looks like this in Hebrew: אה, אני אוהב להיות ליד חוף הים

In the computer's memory, this is stored as אה, אני אוהב להיות ליד חוף הים

    	
	8. 	<big> HTML deprecated element renders the enclosed text at a font size one level larger than the surrounding text (medium becomes large, for example). The size is capped at the browser's maximum permitted font size.

Warning: This element has been removed from the specification and shouldn't be used any more. Use the CSS font-size property to adjust the font size.
	
	EXAMPLE
<p>
  This is the first sentence. <big>This whole
  sentence is in bigger letters.</big>
</p>
	
	OUTCOME
This is the first sentence. This whole sentence is in bigger letters.

    	9. 	<br>: The Line Break element

The <br> HTML element produces a line break in text (carriage-return). It is useful for writing a poem or an address, where the division of lines is significant.

	EXAMPLE
<p> O’er all the hilltops<br>
    Is quiet now,<br>
    In all the treetops<br>
    Hearest thou<br>
    Hardly a breath;<br>
    The birds are asleep in the trees:<br>
    Wait, soon like these<br>
    Thou too shalt rest.
</p>

	OUTCOME

O’er all the hilltops
Is quiet now,
In all the treetops
Hearest thou
Hardly a breath;
The birds are asleep in the trees:
Wait, soon like these
Thou too shalt rest. 
    	10.	<button>: The Button element

The <button> HTML element represents a clickable button, used to submit forms or anywhere in a document for accessible, standard button functionality.

By default, HTML buttons are presented in a style resembling the platform the user agent runs on, but you can change buttons' appearance with CSS.

	EXAMPLE
<button class="favorite styled"
        type="button">
    Add to favorites
</button>

	BLOCK ELEMENT
Block-level elements

In this article, we'll examine HTML block-level elements and how they differ from inline-level elements.

HTML (Hypertext Markup Language) elements historically were categorized as either "block-level" elements or "inline-level" elements. Since this is a presentational characteristic it is nowadays specified by CSS in the Flow Layout. A Block-level element occupies the entire horizontal space of its parent element (container), and vertical space equal to the height of its contents, thereby creating a "block".

Browsers typically display the block-level element with a newline both before and after the element. You can visualize them as a stack of boxes

			
		LIST OF "BLOCK" ELEMENT
	
	1.	<address>: The Contact Address element

The <address> HTML element indicates that the enclosed HTML provides contact information for a person or people, or for an organization.
Contact information.

	EXAMPLES
<p>Contact the author of this page:</p>

<address>
  <a href="mailto:jim@rock.com">jim@rock.com</a><br>
  <a href="tel:+13115552368">(311) 555-2368</a>
</address>

	OUTCOME
Contact the author of this page:
jim@rock.com
(311) 555-2368


	2.	<article>: The Article Contents element

The <article> HTML element represents a self-contained composition in a document, page, application, or site, which is intended to be independently distributable or reusable (e.g., in syndication). Examples include: a forum post, a magazine or newspaper article, or a blog entry, a product card, a user-submitted comment, an interactive widget or gadget, or any other independent item of content.
Article content.

	EXAMPLE
<article class="forecast">
    <h1>Weather forecast for Seattle</h1>
    <article class="day-forecast">
        <h2>03 March 2018</h2>
        <p>Rain.</p>
    </article>
    <article class="day-forecast">
        <h2>04 March 2018</h2>
        <p>Periods of rain.</p>
    </article>
    <article class="day-fo
recast">
        <h2>05 March 2018</h2>
        <p>Heavy rain.</p>
    </article>
</article>

	OUTCOME
Weather forecast for Seattle
03 March 2018

Rain.
04 March 2018

Periods of rain.
05 March 2018

Heavy rain.

	3,	<aside>: The Aside element

The <aside> HTML element represents a portion of a document whose content is only indirectly related to the document's main content. Asides are frequently presented as sidebars or call-out boxes.

	EXAMPLE
<p>Salamanders are a group of amphibians with a lizard-like appearance, including short legs and a tail in both larval and adult forms.</p>

<aside>
    <p>The Rough-skinned Newt defends itself with a deadly neurotoxin.</p>
</aside>

<p>Several species of salamander inhabit the temperate rainforest of the Pacific Northwest, including the Ensatina, the Northwestern Salamander and the Rough-skinned Newt. Most salamanders are nocturnal, and hunt for insects, worms and other small creatures.</p>

	OUTCOME
Salamanders are a group of amphibians with a lizard-like appearance, including short legs and a tail in both larval and adult forms.

The Rough-skinned Newt defends itself with a deadly neurotoxin.

Several species of salamander inhabit the temperate rainforest of the Pacific Northwest, including the Ensatina, the Northwestern Salamander and the Rough-skinned Newt. Most salamanders are nocturnal, and hunt for insects, worms and other small creatures.


Aside content.

	4.	
Long ("block") quotation.

	5.	<details>: The Details disclosure element

The <details> HTML element creates a disclosure widget in which information is visible only when the widget is toggled into an "open" state. A summary or label must be provided using the <summary> element.

A disclosure widget is typically presented onscreen using a small triangle which rotates (or twists) to indicate open/closed status, with a label next to the triangle. The contents of the <summary> element are used as the label for the disclosure widget.

	EXAMPLE
<details>
    <summary>Details</summary>
    Something small enough to escape casual notice.
</details>


Disclosure widget.

	6.	<dialog>: The Dialog element

The <dialog> HTML element represents a dialog box or other interactive component, such as a dismissible alert, inspector, or subwindow
Dialog box.

	EXAMPLE
<dialog>: The Dialog element

The <dialog> HTML element represents a dialog box or other interactive component, such as a dismissible alert, inspector, or subwindow


	7,	<dd>: The Description Details element

The <dd> HTML element provides the description, definition, or value for the preceding term (<dt>) in a description list (<dl>).
Describes a term in a description list.

	EXAMPLE
<p>Cryptids of Cornwall:</p>

<dl>
    <dt>Beast of Bodmin</dt>
    <dd>A large feline inhabiting Bodmin Moor.</dd>

    <dt>Morgawr</dt>
    <dd>A sea serpent.</dd>

    <dt>Owlman</dt>
    <dd>A giant owl-like creature.</dd>

	OUTCOME
Cryptids of Cornwall:

Beast of Bodmin
    A large feline inhabiting Bodmin Moor.
Morgawr
    A sea serpent.
Owlman
    A giant owl-like creature.

	
	8.	<div>: The Content Division element

The <div> HTML element is the generic container for flow content. It has no effect on the content or layout until styled in some way using CSS (e.g. styling is directly applied to it, or some kind of layout model like Flexbox is applied to its parent element).	
Document division.

	EXAMPLE
<div class="warning">
    <img src="/media/examples/leopard.jpg"
         alt="An intimidating leopard.">
    <p>Beware of the leopard</p>
</div>


	9.	<dl>: The Description List element

The <dl> HTML element represents a description list. The element encloses a list of groups of terms (specified using the <dt> element) and descriptions (provided by <dd> elements). Common uses for this element are to implement a glossary or to display metadata (a list of key-value pairs).
Description list.

	EXAMPLE
<p>Cryptids of Cornwall:</p>

<dl>
    <dt>Beast of Bodmin</dt>
    <dd>A large feline inhabiting Bodmin Moor.</dd>

    <dt>Morgawr</dt>
    <dd>A sea serpent.</dd>

    <dt>Owlman</dt>
    <dd>A giant owl-like creature.</dd>
</dl>

	OUTCOME
Cryptids of Cornwall:

Beast of Bodmin
    A large feline inhabiting Bodmin Moor.
Morgawr
    A sea serpent.
Owlman
    A giant owl-like creature.



	10.	<dt>: The Description Term element

The <dt> HTML element specifies a term in a description or definition list, and as such must be used inside a <dl> element. It is usually followed by a <dd> element; however, multiple <dt> elements in a row indicate several terms that are all defined by the immediate next <dd> element.

The subsequent <dd> (Description Details) element provides the definition or other related text associated with the term specified using <dt>.

	EXAMPLE
<p>Please use the following paint colors for the new house:</p>

<dl>
    <dt>Denim (semigloss finish)</dt>
    <dd>Ceiling</dd>
 
    <dt>Denim (eggshell finish)</dt>
    <dt>Evening Sky (eggshell finish)</dt>
    <dd>Layered on the walls</dd>
</dl>

	OUTCOME
Please use the following paint colors for the new house:

Denim (semigloss finish)
    Ceiling
Denim (eggshell finish)
Evening Sky (eggshell finish)
    Layered on the walls




    Description list term.

