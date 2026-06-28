# [Ash] - Mzulft bolt-caster v1.0.1
## Specs
| Name                | Value        |
|---------------------|--------------|
| Magazine Size       | 10           |
| Normal Damage       | 100          |
| Haze Damage         | 75           |
| Velocity            | 200          |
| Rounds Per Minute   | 80           |
| Reload Time (Clip)  | 2.15 seconds |
| Reload Time (Single)| 0.6 seconds  |

### Features
- **Haze**: Deals 75 damage in a small area with a 0.4 meter radius (enabled in Raycast Mode only).
- **Raycast/Prim Mode**: Toggle between physics-based projectiles and raycast hit detection.
- **Bayonet**: Fixable bayonet for melee combat.
- **Partial Reload**: Can reload single rounds or clips depending on ammo count.

## Commands
All Commands Are On Channel 1.

| KeyBind       | Chat Command   | Description                                                 
|---------------|----------------|-------------------------------------------------------------
| —             | help           | Display help message                                        
| Shift + 1     | d              | Draw weapon                                                
| Shift + 2/3/4 | s              | Sling weapon                                                
| R             | r              | Reload                                                      
| Q             | aux            | Toggle between Raycast and Prim mode                        
| 1             | fm             | Enable/Disable Haze (RC mode only)                          
| —             | chat           | Toggles ammo state chat feedback for reloading              
| —             | partial reload | Toggles Partial Reload Mode                                 
| —             | rez            | Toggles Brass and Clip rez on/off                           
| —             | REDSMOKE       | Fix/Unfix Bayonet                                           
| —             | reset          | Reset Script                                                
