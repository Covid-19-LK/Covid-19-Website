<h1 align="center">Covid 19 Statistics Web</h1>
<p align="center">
<img src="https://user-images.githubusercontent.com/79355885/126430024-d34cde97-f3de-4ac6-8383-5d3bfd71e9eb.png" align="center" alt="Logo Image" width="500">
</p>


<div class="section-title style-two text-center">
                <h2 class="title wow pixFadeUp">API which provides the current real time situation <br> of the COVID-19 patients reported in Sri Lanka.</h2>

            </div><!-- /.section-title -->
            <div class="row no-gutters">
                <div class="col-md-8 offset-md-2">
                    <div class="row no-gutters">
                        <div class="col-md-12 text-center mb-4">
                            <input type="text" value="https://hpb.health.gov.lk" readonly class="url-field mb-2">
                            <h4>HOST</h4>
                        </div>
                        <div class="col-md-12 text-center mb-4">
                            <input type="text" value="GET https://hpb.health.gov.lk/api/get-current-statistical" readonly class="url-field mb-2">
                            <h4>EndPoint</h4>
                        </div>
                        <div class="col-md-12 text-center my-3">
                            <h4>Overall details</h4>
                            <div class="row">
                                <table class="w-100 api-table table table-bordered">
                                    <tbody class="text-left">
                                        <tr>
                                            <td>local_new_cases</td>
                                            <td>Confirmed COVID-19 cases reported during the day</td>
                                        </tr>
                                        <tr>
                                            <td>local_active_cases</td>
                                            <td>Confirmed COVID-19 cases currently on treatment at the Hospitals in Sri Lanka</td>
                                        </tr>
                                        <tr>
                                            <td>local_total_cases</td>

                                            <td>Cumulative count of confirmed COVID-19 cases in Sri Lanka</td>
                                        </tr>
                                        <tr>
                                            <td>local_deaths</td>
                                            <td>Total deaths due to COVID-19 reported in Sri Lanka</td>
                                        </tr>
                                        <tr>
                                            <td>local_recovered</td>
                                            <td>Total COVID-19 cases recovered and discharged in Sri Lanka</td>
                                        </tr>
                                        <tr>
                                            <td>local_total_number_of_individuals_in_hospitals</td>
                                            <td>Total suspected COVID-19 cases currently under investigations in hospitals</td>
                                        </tr>
                                        <tr>
                                            <td>global_new_cases</td>
                                            <td>Global confirmed COVID-19 cases reported during last 24 hours</td>
                                        </tr>
                                        <tr>
                                            <td>global_total_cases</td>
                                            <td>Total global confirmed COVID-19 cases</td>
                                        </tr>
                                        <tr>
                                            <td>global_deaths</td>
                                            <td>Total global deaths due to COVID-19</td>
                                        </tr>
                                        <tr>
                                            <td>global_new_deaths</td>
                                            <td>Global deaths due to COVID-19 reported during last 24 hours</td>
                                        </tr>
                                        <tr>
                                            <td>global_recovered</td>
                                            <td>Total Global COVID-19 cases who recovered</td>
                                        </tr>
                                    </tbody>
                                </table>
                            </div>
                        </div>
                        <div class="col-md-12 text-center my-3">
                            <h4>Sri Lankan hospitals overview</h4>
                            <div class="row">
                                <table class="w-100 api-table table table-bordered">
                                    <tbody class="text-left">
                                        <tr>
                                            <td>cumulative_local</td>
                                            <td>Total number of Sri Lankans who have been treated /observed for COVID-19 in a given hospital</td>
                                        </tr>
                                        <tr>
                                            <td>cumulative_foreign</td>
                                            <td>Total number of foreigners who have been treated /observed for COVID-19 in a given hospital</td>
                                        </tr>
                                        <tr>
                                            <td>treatment_local</td>
                                            <td>Total number of Sri Lankans who are currently on treatment/observation for COVID-19 in a given hospital</td>
                                        </tr>
                                        <tr>
                                            <td>treatment_foreign</td>
                                            <td>Total number of foreigners who are currently on treatment/observation for COVID-19 in a given hospital</td>
                                        </tr>
                                    </tbody>
                                </table>
                            </div>
                        </div>
                        <div class="col-md-12">
                            <h4 class="code-toggle">Sample Data<span></span></h4>
                            <pre class="code-element">
                                {
                                    "success": true,
                                    "message": "Success",
                                    "data": {
                                        "update_date_time": "2020-03-17 08:14:26",
                                        "local_new_cases": 10,
                                        "local_total_cases": 29,
                                        "local_total_number_of_individuals_in_hospitals": 3,
                                        "local_deaths": 0,
                                        "local_recovered": 1,
                                        "global_new_cases": 13903,
                                        "global_total_cases": 167511,
                                        "global_deaths": 6606,
                                        "global_recovered": 862,
                                        "hospital_data": []
                                    }
                                }
                                </pre>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <!-- /.container -->
    </section>











# What does it show ?
* Local Covid 19 Informations
* Globle Covid 19 Informations
