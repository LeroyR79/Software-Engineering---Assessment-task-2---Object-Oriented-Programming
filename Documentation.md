## Part A - Data Selection and Game Attributes 
|Attribute      | Data Type    | Measured In    | 
| ------------  | ------------ | -------------- |
|Kilometers     | Integer      | Km             |
|Price          | Float        | $              |
|Top Speed      | Integer      | Km             |
|Estimated Range| Integer      | Km             |
|Year Produced  | Integer      | Year           |

Rank of Importance is listed on the table:
- Km,
- Price,
- Top Speed, 
- Estimated Range,
- Year produced.

#### When comparing: All of Kilometers and price win points when they are lower than the other players card. Top Speed, Estimated Range and Year Produced all win points when they are higher than the others players card.


 
**Attribute explanation:** I have picked these attributes because of their general importance when buying a car. These attributes are pretty fair when it comes to comparing the different cars. 
 Although, some of these attributes, such as Price and Km, may vary depending on the specific car that is used for the cards. These attributes are also very important when makina game like top trumps fair as when some of these attributes are higher, there are others that may be lower in result of that. 
E.g. A lower price of a car is likely to have more Kilometers on the car and a lower estimated range.


## Part B - Class Design

<img width="752" height="602" alt="Part C - Class Diagram" src="https://github.com/user-attachments/assets/9864f669-82d7-4c18-b58d-594e57c3cb0b" />



## Part C - Class Diagram

<img width="292" height="632" alt="Part C - Class Design" src="https://github.com/user-attachments/assets/7f4acb35-408f-437e-b536-ef1173d6abea" />

## Part D - Game Mechanics Design
**Game Explanation**: At the start of the game each player is dealt cards from the deck. A player will then pick an attribute to compare, each player will then pick a card to compare with the attribute that the player has picked. If a draw occurs, the cards from that round will be set aside and no players will gain any cards from the round, the cards will then be collected by the player who wins the round the follows the drawing round.

**Game Balance:** The cards and the game will be balanced by allowing each card to have a specific attribute that makes it better than another car. This will help to avoid having one card as a "trump" card that will beat every other card no matter what attribute is chosen.

## Part E - Interface and Card Design

#### Card Design

<img width="1108" height="563" alt="Part E - Card Design" src="https://github.com/user-attachments/assets/0438f559-f282-4655-9eeb-34c46e0bfa6c" />

#### Interface Design

<img width="818" height="468" alt="Part E - Interface Design" src="https://github.com/user-attachments/assets/37362b15-7ec3-4117-a579-d8d1253a4dae" />

