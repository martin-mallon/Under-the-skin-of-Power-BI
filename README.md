<h1>Under the skin of Power BI</h1>

<br>

<p align="center" width="100%">
    <img width="100%" src="/PBI_Under_the_Skin/Assets/thumbnail.jpeg">
</p>

<br>


<h3>Connecting to data</h3>
  
<p>A navigation system is built using buttons and URL actions. This feature enables users to navigate worksheets using the persistant header buttons or by clicking a graph to reveal related analysis. The <b><code>persistant header</code></b> feature is a solution to the UI complexity and space inefficiencies inherent in a Tableau Story, replacing the clunky grey slider with a sleek, minimalist navigation that does not change. And by integrating <b><code>URL actions</code></b> on graphs, users can conveniently drill explore further the metrics and trends that are eye catching, without having to consider where and how to navigate to related analysis.</p>

<p align="center" width="100%">
    <img width="50%" src="/PBI_Under_the_Skin/Assets/get_data.png">
</p>

<br>

<h3>Managing relationships</h3>
  
<p>Dashboard actions are diverse features that allow interactivity outside of a worksheets domain. Dashboard actions will run on three different run on options: select (clicking with your mouse button), hover (moving your mouse cursor over a mark or header) and menu (a text link within the tooltip to activate the dashboard action). This report uses <b><code>filter actions</code></b> and <b><code>highlight actions</code></b> to emphasise relavant analysis.</p>

<p align="center" width="100%">
    <img width="75%" src="/PBI_Under_the_Skin/Assets/manage_relationships.png">
</p>

<br>

<h3>Building KPIs</h3>
  
<p>These are standard filters that are created from one of the views in your desktop and then applied to more than the original worksheet. The term global filter implies that the filter affects every single view in that dashboard, but that’s not necessarily the case. They could apply to as little as two views, the original view and another. See how "Device" and "Marketing Channel" are transformed from a drop down filter to an interactive viz that operates as a <b><code>global filter</code></b> when clicked.</p>

<code>progression_to_PaymentSuccess__% = DIVIDE(SUM('Data_Summary'[page_Payment_Success]),SUM('Data_Summary'[session_MyAct]))</code>

<br>

<h3>Visualising data</h3>
  
<p>These are standard filters that are created from one of the views in your desktop and then applied to more than the original worksheet. The term global filter implies that the filter affects every single view in that dashboard, but that’s not necessarily the case. They could apply to as little as two views, the original view and another. See how "Device" and "Marketing Channel" are transformed from a drop down filter to an interactive viz that operates as a <b><code>global filter</code></b> when clicked.</p>

<p align="center" width="100%">
    <img width="75%" src="/PBI_Under_the_Skin/Assets/basic_viz.png">
</p>

<br>

<h3>Custom formatting</h3>
  
<p>These are standard filters that are created from one of the views in your desktop and then applied to more than the original worksheet. The term global filter implies that the filter affects every single view in that dashboard, but that’s not necessarily the case. They could apply to as little as two views, the original view and another. See how "Device" and "Marketing Channel" are transformed from a drop down filter to an interactive viz that operates as a <b><code>global filter</code></b> when clicked.</p>

<p align="center" width="100%">
    <img width="50%" src="/PBI_Under_the_Skin/Assets/custom_format.png">
</p>
