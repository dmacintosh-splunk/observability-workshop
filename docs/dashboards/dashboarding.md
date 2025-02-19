# Adding Notes and Dashboard Layout

## 1. Adding Notes

Often on dashboards it makes sense to place a short "instruction" pane that helps users of a dashboard.

Lets add one now by clicking on the **New Text Note**{: .label-button.sfx-ui-button-grey} Button.

![three charts](../images/dashboards/M-MoreCharts-10.png)

This will open the notes editor.

![Notes 1](../images/dashboards/M-Notes-1.png)

To allow you to add more then just text to you notes, Splunk is allowing you to use Markdown in these notes/panes.
Markdown is a lightweight markup language for creating formatted text using plain-text often used in Webpages.

This includes (but not limited to):

* Headers. (in various sizes)
* Emphasis styles.
* Lists and Tables.
* Links. These can be external webpages (for documentation for example) or directly to other Splunk IMT Dashboards

Below is an example of above Markdown options you can use in your note.

=== "Sample Markdown text"

    ```text

    # h1 Big headings
    ###### h6 To small headings

    ##### Emphasis

    **This is bold text**, *This is italic text* , ~~Strikethrough~~

    ##### Lists

    Unordered

    + Create a list by starting a line with `+`, `-`, or `*`
    - Sub-lists are made by indenting 2 spaces:
    - Marker character change forces new list start:
        * Ac tristique libero volutpat at
        + Facilisis in pretium nisl aliquet
    * Very easy!

    Ordered

    1. Lorem ipsum dolor sit amet
    2. Consectetur adipiscing elit
    3. Integer molestie lorem at massa

    ##### Tables

    | Option | Description |
    | ------ | ----------- |
    | chart  | path to data files to supply the data that will be passed into templates. |
    | engine | engine to be used for processing templates. Handlebars is the default. |
    | ext    | extension to be used for dest files. |

    #### Links

    [link to webpage](https://www.splunk.com)

    [link to dashboard with title](https://app.eu0.signalfx.com/#/dashboard/EaJHrbPAEAA?groupId=EaJHgrsAIAA&configId=EaJHsHzAEAA "Link to the Sample chart Dashboard!")
    ```
Copy the above by using the copy button and paste it in the *Edit* box.
the preview will show you how it will look.

---

## 2. Saving our chart

Give the Note chart a name, in our example we used *Example text chart*, then press the **Save And Close**{: .label-button .sfx-ui-button-blue} Button.

This will bring you back to you Dashboard, that now includes the note

![three charts and note](../images/dashboards/M-Notes-2.png)

---

## 3. Ordering & sizing of charts

If you do not like the default order and sizes of your charts you can simply use window dragging technique to move and size them to the desired location

Grab the **top** border of a chart and you should see the mouse pointer change to a drag icon. You can now simply drag you chart to the desired location. 

![Dragging](../images/dashboards/M-Notes-4.png)

Now drag the **Latency History** Chart to site below the **Latency vs Load** Chart.

!!! info "On the Move"
    The screenshot above is taken in the middle of the Move/Drag action as described above. </br>
    It is **not** meant as the location where you need to save this chart, for that see the screenshot below)

You can also resize a chart, simply by dragging the side or the bottom.

![sizing](../images/dashboards/M-Notes-5.png)

As a last exercise reduce the width of the note chart to about a third of the other charts. The chart will automatically snap to one of the sizes it supports. Widen the 3 other charts to about a third of the Dashboard. Drag the notes to the left of the others and resize it to match it to the 23 others.

Set the time to -1 h hour and you should have the following dashboard!

![TaDA!](../images/dashboards/M-Notes-6.png)

On to Detectors!
