# Optimization   

## Code  
0. For games with dedicated server use multitreding
1. Caching objects  
  Don't use FindObject and similar operations in update  
  Don't use Camera.main in update because it's calls FindObjectWithTag  
2. Use Fly Weight
  Scriptable objects to store static data of same objects    
3. Use objects pooling  
4. Avoid Allocating Memory
   Use string builder
   Use non allocate physics methods
6. Do calculations one time per several frames
7. Use hash values instead of string parameters 
8. Use custom update manager 
   EnemyUpdateManager that calls logic in list of enemies
9. For over Foreach
10. Arrays over Lists
11. Remove Debug.Log() calls with #if UNITY_EDITOR
13. Set camera layers
14. Set physics layers interaction (Turn in Project Settings)   
15. Disable stack trace logging (Turn in Project Settings)
16. Disable transform sync(Turn in Project Settings)
17. Enable reuse collision fallbacks()
18. Change fixed update time
19. Use the incremental garbage collector to split the GC workload (Turn in Project Settings)
20. Manually collect garbage in handy places with System.GC.Collect();
21. Accelerometr tweak (Turn in Project Settings)


## Graphics  

1. Mark Static
2. Use GPU instancing
3. Bake meshes  
4. Bake light
5. Use LOD
6. Low the rendering resolution
7. Tweak shadow distance
8. Tweak camera far plane
9. Use oclussion culling
10. Power of 2 textures
11. Use sprite atlases and color palletes
12. Use light probes
13. Use less materials
14. Split canvases
15. Disable invisable UI
16. Turn of raycattarget for not interactable ui
17. Use simple colliders instead of mesh
18. Use Imposters
   

## Resources
[Optimize Your Mobile Game](https://unity.com/ru/resources/unity-e-book-optimize-your-mobile-game-performance?ungated=true)  
[Unity post](https://blog.unity.com/games/optimize-your-mobile-game-performance-expert-tips-on-graphics-and-assets)  
[Reddit Post](https://www.reddit.com/r/Unity3D/comments/njrqhu/big_thread_of_optimization_tips/)  
[Medium Post](https://medium.com/lonely-vertex-development/how-we-optimised-our-scripts-in-unity-447924863b3a)  
