1.  Do not use font-size at root element such as body,html,\* etc.
2.  Percentage values are always relative to another quantity.
3.  rem => root element
4.  Relation Between <strong>rem</strong> and <strong>em</strong>
    <ul>
        <li>em is relative to parent element</li>
        <li>let's set an example</li>
        <li>
            <code>
                <div>
                    <p></p>
                </div>
            </code>
        </li>
        <li>
            <p>
                If the div's font size is 2rem and p's font size 2rem then there will be no change. Because both are looking for the same root element size which is controlled by browser and that is 1rem or 16px.
            </p>

            <p>
                But if we set div's font size is 2rem and p's font size is 2rem then there is a change we will see. div looking for the root element size (1rem or 16px) but p looking for its parent element size and in our case it is 2rem. Then p's font size will be 2rem  * 2 = 4rem or 64px. If p's font size is 0.5rem then its actual font size is 2rem * 0.5 = 1rem or 16px
            </p>
        </li>

    </ul>

5.  Use <code>em</code> for padding, marging, border. Don't use em
6.  Using percentage is better than vw or vh. Let's set an example. Set body width is 100vh. If we have large content that's shows up vertical scroll and that's fine. The twist is here. For this vertical scroll body don't have any preparation. When vertical scroll appeares, body width will be 100vw+vertical scroll width; and that's why horizontal scroll appeares. But if we set body width is 100% then even after comes up horizontal scroll, body width will remain 100%(including scrollbar widht).
