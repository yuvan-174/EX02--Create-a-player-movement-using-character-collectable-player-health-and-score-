# EX02--Create-a-player-movement-using-character-collectable-player-health-and-score-
# AIM:
 To Create a player movement using character, collectable, player health and score 
 Procedure To Createand Destroythecoin:
# PROCEDURE:
 1. Create a new project in Unreal Engine and choose a template that suits your needs.
 2. Add anewactor to the level and call it "Coin".
 3. Create a new blueprint based on the Coin actor byselecting it in the Content Browser and
 choosing "Create Blueprint".
 4. Openthe Coin blueprint and add a static meshcomponent to represent the coin. You can
 import a 3D model or use one of the default shapes provided by Unreal Engine.
 5. Add acollision component to the Coin blueprint so that the player can interact with it.
 Choose a simple collision shape like a sphere or a box.
 6. Add acollision component to the Coin blueprint so that the player can interact with it.
 Choose a simple collision shape like a sphere or a box.
 7. Create a new blueprint based on the player character byselecting it in the Content
 Browser and choosing "Create Blueprint".
 8. Openthe player blueprint and add a collision component to represent the player's
 interaction with the coins.
 9. Add anevent to the player blueprint that gets triggered when the player collides with a
 coin. Use a collision event and check if the collided actor is a coin.
 10. If the collided actor is a coin, check if it has already been collected. If not, set its
 IsCollected variable to true and add its value to a score variable in the player blueprint.
 11. Remove the coin fromthe level bycalling its Destroy function.
 12. Add several instances of the Coin actor to the level and adjust their positions so that they
 are spread out and not too close to each other
# OUTPUT:
![image](https://github.com/user-attachments/assets/573a6fac-ed1d-4b41-a46e-d4a10690d96e)
![image](https://github.com/user-attachments/assets/7e237bfd-af25-421c-8a61-cd773db30c41)

# RESULT:
 Thus, To Create aplayer movement usingpawn, collectible, player health, and score createdand
 developed by unreal Engine
