# My ERP
## An app made for a better ERP experience.

**My ERP** app is something I started working on after seeing that the official ones omitted some info/data in their UI like marks in SEE.  
I also wanted to manually track things like attendance, marks etc.

So with that in mind, I started developing this app and decided to have at least the following features:
1. Uses the official erp data.
1. Needs to work when offline.  
This is especially useful when the official erp server is down, the app should show the old data/results instead of not working/showing anything at all.
1. Allow manually marking/setting attendance or exam marks as profs etc take time to update the data in erp.
1. Notify when something has updated/changed.  
Say for example, you got 19/20 in IAT/CIE 1 and erp shows it too, but a few days later, it is changed to 15/20.  
Now that's a problem, isn't it? So changes are important and needs to be notified.
1. Needs to have calculators like:
    1. Attendance calculators for:
        - Required classes: How many consecutive classes must I attend to reach 85%?
        - Safe bunk: How many classes can I skip without falling below 85%?
        - Attendance impact: If I miss the next 3 classes, what will my attendance become?
        - Target attendance: What attendance percentage will I have if I attend the next N classes?
        - Minimum attendance: Given the remaining classes, is it still mathematically possible to reach 85%?
        - And more if useful...
    1. CGPA and SGPA related calculators.
