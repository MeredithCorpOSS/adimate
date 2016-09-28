    $('#mydiv').adimate({
        effect: 'hvr-wobble-vertical',
        event: 'hover',
        repeat: 1,
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
3. repeat  - 1 or no of times, if 0 considered infinite 
4. devices - mobile, tablet, desktop, all
4. interval - 

Events
supports multiple events 

             1. onAnimationStart
             
             2. onAnimationStop

             3. onDone
             4. onStart




Methods

1. start() - will run irrespective of event

2. stop()  - will permanently stop the event

3. watch() - will cycle back to event mode

4. get() - 
5. set() -





