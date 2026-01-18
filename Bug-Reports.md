# Bug Reports – Rise of the Humble Knight

---

## BUG-01: Healing Action Cannot Be Reverted During Turn-Based Combat

### Environment
- Engine: Unity 2D
- Platform: PC
- Build: Playable Prototype

### Severity
Medium

### Priority
Medium

### Description
During turn-based combat, when the player selects the healing action from the combat UI, there is no option to cancel or revert the selection before confirming the action.  
If the player selects the healing action by mistake, they are forced to proceed with it, negatively affecting combat flow and player decision-making.

### Steps to Reproduce
1. Start a turn-based combat encounter
2. Wait for the player's turn
3. Select the healing action from the combat UI
4. Attempt to return to the action selection menu

### Expected Result
- The player should be able to cancel the selected action
  OR
- The player should be able to return to the action selection menu before confirming

### Actual Result
- The healing action cannot be reverted
- The player is forced to execute the selected action

### Impact
- Reduces player control during combat
- Negatively affects user experience
- Can lead to unintended combat outcomes

### Evidence
- Video and visual evidence available in the `Evidence` folder

