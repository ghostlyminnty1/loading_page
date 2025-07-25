# loading_page
Please View in code to understand stracture of how to place each items
!!The code should be in "ReplicatedFirst"

A loading screen for roblox game, This one focus on actual loading screen not main menu
To be able to use the code
please add these following before use the code or else Error:
LocalScript
Inside LocalScript add:
   -ScreenGui Inside ScreenGui(LoadingScreen) add:
                 -Frame(name: background) and inside background add Frame named "Bar"
                 -after Bar then add ImageLabel, TextLabel, TextLabelTips(optional)

In LoadingScreen Should look like this
 -background
  -Bar
    -LoadingBar(Frame)
        -BarScript(LocalScript)
  -ImageLabel
    -UIAspectRatioConstraint
  -TextLabel
  -TextLabelTips
     -TipsScript(localScript)

 !!You dont need to add Tips, If not adding Tips Get rid of TextLabelTips+TipsScript Out!!

--
Afterwards, for each code in LocalScript please go to coding side with the following name.
TO make loading screen, Recommned to make it in StarterGui first before move ScreenGui(loadingScreen) into LoadingHandler(main function of loading aka LocalScript)

!!The code should be in "ReplicatedFirst"
