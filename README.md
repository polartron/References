# References
Links to resources I find extra helpful. 

## Networking

Assuming you know the basics like TCP, UDP and Sending Packets. Here are *some* resources to deep dive into.  

https://www.gabrielgambetta.com/client-side-prediction-server-reconciliation.html  
https://www.youtube.com/watch?v=W3aieHjyNvw  
https://www.youtube.com/watch?v=k6JTaFE7SYI  
https://fabiensanglard.net/quake3/network.php  
https://developer.valvesoftware.com/wiki/Source_Multiplayer_Networking  
https://gafferongames.com/post/state_synchronization/  
https://gafferongames.com/post/snapshot_compression/  
https://gafferongames.com/post/snapshot_interpolation/  

## Misc Games

### Flow Field Pathfinding
A clear and concise guide on how Flow Fields work. Useful for simulating large amounts of units like crowds and AI in an RTS. 
https://leifnode.com/2013/12/flow-field-pathfinding/

### Hexagonal Grids
A complete reference guide to making your own **Hexagon Coordinate System**.

https://www.redblobgames.com/grids/hexagons/  
http://www-cs-students.stanford.edu/~amitp/game-programming/grids/

## Misc Other
Sometimes you just want to take it easy and make an API endpoint without all this MVC nonsense. *Get 'er done*. 

#
```cs
    public class HomeModule : CarterModule
    {
        public HomeModule()
        {
            Get("/", async (req, res) => await res.WriteAsync("Hello from Carter!"));
        }
    }
```
https://github.com/CarterCommunity/Carter
