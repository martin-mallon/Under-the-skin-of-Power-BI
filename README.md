<h1>Under the skin of Power BI</h1>

<br>


![thumbnail](https://user-images.githubusercontent.com/88795187/166716360-b5232d63-21c1-47e9-a9a8-c5ce22559e91.jpeg)


<br>


<h3>Connecting to data</h3>
  
<p>A navigation system is built using buttons and URL actions. This feature enables users to navigate worksheets using the persistant header buttons or by clicking a graph to reveal related analysis. The <b><code>persistant header</code></b> feature is a solution to the UI complexity and space inefficiencies inherent in a Tableau Story, replacing the clunky grey slider with a sleek, minimalist navigation that does not change. And by integrating <b><code>URL actions</code></b> on graphs, users can conveniently drill explore further the metrics and trends that are eye catching, without having to consider where and how to navigate to related analysis.</p>

<p align="center" width="100%">
    <img width="33%" src="https://user-images.githubusercontent.com/88795187/166722009-e69de9e8-19fa-4ffa-ad0f-04b8dfa067d4.png">
</p>


<p align="center" width="100%">
    <img width="50%" src="/Basic_Anatomy_of_Power_BI/Assets/get_data.jpeg">
</p>

<br>

<h3>Managing relationships</h3>
  
<p>Dashboard actions are diverse features that allow interactivity outside of a worksheets domain. Dashboard actions will run on three different run on options: select (clicking with your mouse button), hover (moving your mouse cursor over a mark or header) and menu (a text link within the tooltip to activate the dashboard action). This report uses <b><code>filter actions</code></b> and <b><code>highlight actions</code></b> to emphasise relavant analysis.</p>

<br>

<h3>Custom metrics</h3>
  
<p>These are standard filters that are created from one of the views in your desktop and then applied to more than the original worksheet. The term global filter implies that the filter affects every single view in that dashboard, but that’s not necessarily the case. They could apply to as little as two views, the original view and another. See how "Device" and "Marketing Channel" are transformed from a drop down filter to an interactive viz that operates as a <b><code>global filter</code></b> when clicked.</p>

<code>progression_to_PaymentSuccess__% = DIVIDE(SUM('Data_Summary'[page_Payment_Success]),SUM('Data_Summary'[session_MyAct]))</code>

<br>

<h3>Data visualisations</h3>
  
<p>These are standard filters that are created from one of the views in your desktop and then applied to more than the original worksheet. The term global filter implies that the filter affects every single view in that dashboard, but that’s not necessarily the case. They could apply to as little as two views, the original view and another. See how "Device" and "Marketing Channel" are transformed from a drop down filter to an interactive viz that operates as a <b><code>global filter</code></b> when clicked.</p>
