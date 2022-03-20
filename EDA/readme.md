<h1>EDA</h1>
<div>
  <ul> 
    <li>This folder has the notebook which is used to perform EDA.</li>
    <li>ALl the insights which are found in EDA are as follows:<br>
      <ol>
        <li>All of the numrical features are categorical.</li>
        <li>No feature has missing values.</li>
        <li>All the data is recorded in 2018 so it doesn't have any specific significance.</li>
        <li>Data is recorded after each 15 minutes.</li>
        <li>Company starts work from 8 a.m. and completes at 8 p.m. and at 12 p.m. tiffin break is given.</li>
        <li>Rest of the temporal variables have no specific distribution.</li>
        <li>All of the continuous variables are highly skewed.</li>
        <li>All of the numeric features conssists zero therefore log tranformation can't be applied directly on these features.</li>
        <li>Range of all the numeric data is large therefore it's evident that each of the feature may consist outliers.</li>
        <li>Log Transformation can't improve the distribution of the data.</li>
        <li>Lagging_Current_Reactive.Power_kVarh and CO2(tCO2) has some linear relationship with Usage_kWh</li>
        <li>Leading_Current_Reactive_Power_kVarh and Leading_Current_Power_Factor has also some non-linear relationship with Usage_kWh.</li>
        <li>Usage_kWh has high correlation with Lagging_Current_Reactive.Power_kVarh and CO2(tCO2).</li>
        <li>Lagging_Current_Reactive.Power_kVarh also has high correlation with CO2(tCO2).</li>
        <li>Leading_Current_Reactive_Power_kVarh has high correlation with Leading_Current_Power_Factor.</li>
        <li>Target variables has some correlation with all of the numeric variables.</li>
        <li>Beside that, independent variables also has high correlation among them.</li>
        <li>All the continuous features have a lot of outliers so removing all the outliers from the dataset will reduce the dataset extensively.</li>
        <li>Also considering these huge amount of datapoints as outliers isn't a good choice.</li>
        <li>Energy usage is much higher in weekdays that weekend especially at the mid of the week.</li>
        <li>It is also found that usage of energy is directly propotional with Load_Type.</li>
      </ol>
    </li>
  </ul>
</div>
