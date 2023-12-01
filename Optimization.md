# Optimization   

## Code  

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
12. Manually collect garbage in handy places with System.GC.Collect();
13. Set camera layers
14. Set physics layers interaction (Turn in Project Settings)   
15. Disable stack trace logging (Turn in Project Settings)   
16. Use the incremental garbage collector to split the GC workload (Turn in Project Settings)   


##Resources
[Optimize Your Mobile Game](https://unity.com/ru/resources/unity-e-book-optimize-your-mobile-game-performance?ungated=true)
[Reddit Post] (https://www.reddit.com/r/Unity3D/comments/njrqhu/big_thread_of_optimization_tips/)
[Medium Post] (https://medium.com/lonely-vertex-development/how-we-optimised-our-scripts-in-unity-447924863b3a)
