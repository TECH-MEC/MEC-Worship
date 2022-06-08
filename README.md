# Welcome to MEC Worship Project
## A Sheet Music Management and Sharing App

App Name : MEC Worship (Working Title)
Customer : MEC
Development Team :
* Adam Atein
* Jad Haddad
* Abdallah Shmaitelly

----
### Application Description
MEC Worship is a music platform made for worship leaders across the globe. It aims at giving worship leaders a place to create, discover, and make use of music sheets for worship. It's also aimed at spreading new and old Lebanese hymns that were previously exclusive to the Churches in which they were created in.

### Functional Specifications
Before listing the functionalities it is important to take a step back and list all of the entities and their descriptions so that they may be used in describing the functionalities of the application.

#### Entities
|  Entity   | Description                                                      |
|:---------:|:---------------------------------------------------------------- |
|  Viewer   | Anyone                                                           |
| Free User | Anyone with an Account                                           |
| Paid User | User that has Paid                                               |
| Moderator | User that Approves Songs                                         |
|   Admin   | User that has Moderator privileges and can add/remove Moderators |

**Viewer** can become **Free User** by signing up.
**Free User** can become **Paid User** by paying a one time fee
**Free User** or **Paid User** can apply to be **Moderator**
**Moderator** has to be approved by **Admin**
**Admin** are set by **MEC Worship Team**

#### Features

|     View     | Features                                                            |
|:------------:|:------------------------------------------------------------------- |
| Landing Page | Picture Banner                                                      |
|              | Text about Us                                                       |
|              | Top Lists                                                           |
|              | If user shows your lists                                            |
|   Discover   | Search Bar                                                          |
|              | Blocks to select different genres                                   |
|    Genre     | Top Songs in the Genre                                              |
|              | List of available songs in the genre                                |
|              | List of Genre Artists                                               |
|    Songs     | Song title                                                          |
|              | Song Metadata                                                       |
|              | Lyrics for the song with chords                                     |
|              | Transpose Chords Up and Down                                        |
|              | Play a sample of the song                                           |
|              | Download button for Presentation                                    |
|              | Download button for PDF                                             |
|              | See the chord Diagrams for the Songs                                |
|              | Ability to add notes/comments                                       |
|              | Song with notes (if available)                                      |
|              | Embedded Video (if available)                                       |
|              | Ability to request making the song public (If yours and not public) |
|              | Add to set list                                                     |
|              | Share song                                                          |
|              | Report song                                                         |
|   Set List   | List of songs in the setlist                                        |
|              | If its yours you can also edit its content                          |
|              | You can share setlist with people on the app                        |
|              | You can download a whole set (Why! Risk?)                           |
|              | Add to group                                                        |
|              | Toggle public or private                                            |
|              | Set List Title                                                      |
|              | Flag if anything inappropriate                                      |
|    Group     | List of the setlists                                                |
|              | Share Button                                                        |
|              | If its yours you can also edit its content                          |
|    Artist    | List of the songs they made                                         |
|              | A short description about the artist                                |
|              | Artists Name and Photo                                              |
|  User Page   | Profile information                                                 |
|              | Edit User info button                                               |
|              | List of your Songs and ability to add new ones                      |
|              | List of your Set Lists and ability to add new ones                  |
|              | List of your Groups and ability to add new ones                     |
|              | List of your favorite songs                                         |
|              | List of your favorite Set Lists                                     |
|              | Your user ID                                                        |
|              | Request to become moderator                                         |
|              | Moderator Request Form                                              |
|  Other User  | List of his public set lists                                        |
| Create Song  | Fields for Metadata                                                 |
|              | Field for Chords                                                    |
|              | Field for Lyrics                                                    |
|              | Section to create presentations                                     |
|              | Save button                                                         |
|              | Field for uploading audio sample                                    |
|              | Field for embedded video                                            |
|   Sign Up    | Field for email                                                     |
|              | Field for first and last name                                       |
|              | Field for password and password validation                          |
|              | Already have account sign in                                        |
|   Sign In    | Field for email                                                     |
|              | Field for password                                                  |
|              | Forgot password                                                     |
|              | Don't have account sign up                                          |
|  Dashboard   | List of open requests to add songs                                  |
|              | List of open song reports                                           |
|              | List of open set list flags                                         |
|              | If Admin ability to accept moderators                               |
|   Contacts   | Add Contact with ID                                                 |
|              | List of Contacts                                                    |
|              | Click on a contact to chat                                          |
|     Chat     | Text field                                                          |
|              | Chats last a Month                                                  |
