# spy-game
find 007 in list nums then return TRUE, otherwise return False

def spy_game(nums):
    
    spy=False
    
    for haha in range(len(nums)-2):
        
        if nums[haha] == 0 and nums[haha+1] == 0 and nums[haha+2] == 7:
            spy=True
            break
        else:
            pass
       
            
    return spy                
            
  
Results: 
    spy_game([1,2,4,0,0,7,5]) --> True
    spy_game([1,0,2,4,0,5,7]) --> True
    spy_game([1,7,2,0,4,5,0]) --> False
