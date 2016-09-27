    $('#mydiv').adimate({
        effect: 'hvr-wobble-vertical',
        event: 'hover',
        repeat: 'once',
    });

Input 

1. effect  - name of the event we support(mostly from hover.css)
             It can also support custom css class name as string or 
             an object with in and out parameters 

             eg:- 'hvr-wobble-vertical' 
                   or
                 {
                    'in' : 'myres-zoom',
                    'out': 'myres-zommout'
                 }
2. event   - on what event do we need to execute the effect
             supported values 'hover', 'infullviewport', 'inpartialviewport', 'load'
3. repeat  - once, continious or no of times
4. devices - mobile, tablet, desktop, all
5. notify  - supports multiple events 

             1. onEnter()
             
             2. onLeave()
             
             3. onDone()




Returns

1. start() - will run irrespective of event

2. stop()  - will permanently stop the event

3. watch() - will cycle back to event mode





