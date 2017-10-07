# .entropy

#### _An interactive cyberpunk short story where the user can enter a name, choose between Order and Chaos, and receive one of two endings based on their choices._

#### James Osborn, _Project Lead_
#### Scott Reichert, _Design/Production_
#### Elliot Buren, _UI Lead_
#### Joseph Tomlinson, _Engineering Lead_

## Description

_.entropy is an interactive cyberpunk story that focuses on the themes of order and chaos. The player is first presented with an intro that sets up the world and story, then they are taken to a character creation page._

_On the character creation page, the user must choose between one of two paths, Order or Chaos, and then must enter a name. The choice the player makes here will have some impact on the story later on. The name the user selects will appear at certain points throughout the story. The user must select a path, and enter a name (1 or more characters, 40 max)._

_As the user progresses through the story, there is a glyph on the side of the page that links to a glossary of cyberpunk terms. If the user is unsure of a certain word, they can use this glossary to get a better understanding._

_There is a creation page followed by 7 unique scenes, in which the user will be tasked with making a variety of decisions. Depending on the choices they make throughout the story, there will be some impact on the outcome of the story._

_Once the user reaches the final scene, they are given a difficult choice between 2 different ending OR presented with only one option, depending on the choices they made throughout the story._

## Known Bugs

_Glossary is broken_  
_hoverbike1.mp3 does not play_  

## Expansions/Updates

1. .entropy update -- 10/8/17  
__New name__ the story title has been changed to closer reflect the themes explored, The . appears before entropy as if it were a method in a coding language   
__Editted story text__ Shorten and condense the story text to make the story flow faster,  
__apply the 'rule of 20'__ no scene should be longer than 20 lines of text, to speed up story flow  
__Original screenshots__ taken from custom maps on Garry's Mod.    
__Original sounds__ hoverbike1.mp3 now plays whenever the player starts their hoverbike, the 85 Wizzer.

2. glossary update -- ?  
__glossary glyph__ a book glyph linking to a glossary of cyberpunk terms will hug the right side of the page, following the player as they scroll up and down

3. dungeons update -- ?  
__2 unique dungeons__ depending on if the player is Order or Chaos, they will be given the option to hack in to FrameWorld and experience one of two unique text "dungeons", with a variety of puzzles using JavaScript. They are:  _Court of the Blizzard Queen_ if the player is Order, _101010_ in the player is Chaos.
4. art, music and sound update -- 11/20/17  
after game jam


## Support and contact details

_You can contact the developers if you have an problems with this program. jamescarlosborn@gmail.com_  

## Technologies Used

#### License

*Determine the license under which this application can be used.*

# Specs
| Spec                                                                                                                    | Example Input:                                            | Example Output:                                                                                                                      |
|-------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------|
| The program presents the user with a form where they can enter their name.                                          | User enters the name "Jose"                               | The user's name appears in text throughout the story.                                                                                       |
| The program presents the user with a form where they can enter their archetype.                                     | User picks Order or Chaos path.                           | Depending on path chosen, user is presented with unique options related to their path.                                               |
| If the user doesn't select an archetype, or the name they enter is too short or too long, they are prevented from advancing to the first scene.              | User enters no name.                                      | USER_ERROR[ID:32]='NAME TOO SHORT'                                                                                                   |
| When the user clicks on the Submit button on character creation, they are taken to the first "story scene."                               | User clicks Submit button.                                | User is taken to first "story scene."                                                                                                |
| The user can choose between two options that will bring them to different story scenes.                             | User chooses to "go to bar".                              | User is given a scene that branches away from the main story, giving the user choices.                                               |
| Selecting certain options will allow or disallow options later on.                                                  | User chooses the "Order" path.                            | User is not allowed to "go berserk" later in the story.                                                                              |
| The program will give the user 1 option for story ending depending on what choices they made throughout the story.  | User chooses only "Chaos" options throughout the story.   | User is presented with the option to see only Ending 1 (Chaos).                                                                      |
| The program will give the user 2 options for story ending depending on what choices they made throughout the story. | User chooses mostly "Order" options throughout the story. | User is presented with the option of Ending 1 (Chaos) or Ending 2 (Order).                                                           |
| The user can click on a glyph on the side of the page to access a cyberpunk glossary of terms.                      | User clicks on a book glyph on side of page.              | User gets a pop-up window with a glossary of cyberpunk terms which they can close at any time and return immediately to their scene. |
| Certain buttons will not take the user to a new page, but provide additional "flavor text."                         | User picks the option to 'stay at home.'                  | User is shown the text "You really need to meet Jam @ the Jealous Englishman."                                                       |
| The user is shown a unique intro before the character creation page, where text is scrolling upwards across the screen. | User goes to index.html.                                  | Intro is played, text flows vertically up screen, after intro user is taken to character creation.                                   |
### The program presents the user with a form where they can enter their name.
Example Input: User enters the name "Jose"
Example Output: Scene A-- Hello, Jose. Welcome to Velvet City.

### The program presents the user with a form where they can enter their archetype.
Example Input: User picks Order or Chaos path.
Example Output: Depending on path chosen, user is presented with unique options related to their path.

### If the user doesn't select an archetype or name, they are prevented from advancing to the first scene.

Example Input: User enters no name.
Example Output: USER_ERROR[ID:32]='NAME TOO SHORT'

### When the user clicks on the Submit button, they are taken to the first "story scene."
Example Input: User clicks Submit button.
Example Output: User is taken to first "story scene."

### The user can choose between two options that will bring them to different story scenes.
Example Input: User chooses to "go to bar".
Example Output: User is given a scene that branches away from the main story, giving the user choices.

### Selecting certain options will allow or disallow options later on.
Example Input: User chooses the "Order" path.
Example Output: User is not allowed to "go berserk" later in the story.

### The program will give the user 1 option for story ending depending on what choices they made throughout the story.
Example Input: User chooses only "Chaos" options throughout the story.
Example Output: User is presented with the option to see only Ending 1.

### The program will give the user 2 options for story ending depending on what choices they made throughout the story.
Example Input: User chooses mostly "Order" options throughout the story.
Example Output: User is presented with the option of Ending 1 (Chaos) or Ending 2 (Order).

### The user can click on a glyph on the side of the page to access a cyberpunk glossary of terms.
Example Input: User clicks on a book glyph on side of page.
Example Output: User gets a pop-up window with a glossary of cyberpunk terms which they can close at any time and return immediately to their scene.

### Certain buttons will not take the user to a new page, but provide additional "flavor text."
Example Input: User picks the option to 'stay at home.'
Example Output: User is shown the text "You really need to meet Jam @ the Jealous Englishman."

### The user is shown a unique intro before the character creation page, where text is scrolling upwards across the screen.
Example Input: User goes to index.html.
Example Output: Intro is played, text flows vertically up screen, after intro user is taken to character creation.
