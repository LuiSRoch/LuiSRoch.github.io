---
layout: post
title:  "Data"
ref: Data-Source
lang: en
---

<div class="poweredBy" style="font-family: Arial, Helvetica, sans-serif;"><span style="font-size: 15px;color: #333333;text-decoration: none;">Data provided by <a href="https://fred.stlouisfed.org/" rel="nofollow" target="_blank" style="font-size: 15px;color: #06529D; font-weight: bold;" class="underline_link" align="right">Federal Reserve Bank of St. Louis</a></span>
<br />
  <a href="https://fred.stlouisfed.org/tags/series"><strong>528,000</strong> US and international time series</a> from <a href="https://fred.stlouisfed.org/sources"><strong>87</strong> sources</a>
  <br />
  <form action="https://fred.stlouisfed.org/search?st=&404-search-button=Search" method="GET">
    <input type="text" id="search" name="st" placeholder="Search FRED data e.g., gdp, inflation, unemployment">
    <button type="submit" id="submit" style="background-color:#687f9f;color:white">Search</button>
  </form>
</div>

<br />
  <meta content="width=device-width, initial-scale=1.0" name="viewport">
  <iframe style="border: 1px solid #333333; overflow: hidden; width: 100%; height: 245px;" src="//research.stlouisfed.org/fred-glance-widget.php" height="450" width="100%" frameborder="0" scrolling="yes"></iframe>
<hr>
<br />

<div class="poweredBy" style="font-family: Arial, Helvetica, sans-serif;"><span style="font-size: 15px;color: #333333;text-decoration: none;">Data provided by <a href="https://www.bea.gov" rel="nofollow" target="_blank" style="font-size: 15px;color: #06529D; font-weight: bold;" class="underline_link" align="right">Bureau of Economic Analysis</a></span>
<br />
  <form action="https://search.bea.gov/search?utf8=%E2%9C%93&affiliate=u.s.bureauofeconomicanalysis&query=&commit=search" method="GET">
    <input type="search" id="edit-keys" name="query" placeholder="Search BEA data e.g., GDP, Personal Income, International Trade...">
    <button type="submit" id="btnSearch" style="background-color:#687f9f;color:white">Search</button>
  </form>
</div>
<br />
<hr>

<br />
<div class="poweredBy" style="font-family: Arial, Helvetica, sans-serif;"><span style="font-size: 15px;color: #333333;text-decoration: none;"> Data provided by <a href="https://www.fincen.gov/" rel="nofollow" target="_blank" style="font-size: 15px;color: #06529D; font-weight: bold;" class="underline_link" align="right">Financial Crimes Enforcement Network</a></span>
  <form action="https://www.fincen.gov/search/node?keys=&404-search-button=Search" method="GET">
    <input type="text" id="search" name="keys" placeholder="Search FINCEN data e.g., SARS, fraud, insurance">
    <button type="submit" id="submit" style="background-color:#687f9f;color:white">Search</button>
  </form>
</div>

<div class="w3-padding w3-xlarge w3-orange">
  <b >Suspicious Activity Report Statistics (SAR Stats)</b>
  <b > | </b>
  <b >FAQ/Glossary</b>

  <div id="formButtonContainer">
  	<div id="formButtons">
      <label style="display:none;" for="formButtonGenerate">Generate</label>
  		<form action="https://www.fincen.gov/fcn/Reports/SARStats" method="GET"><button id="formButtonGenerate" class="formButton btn btn-primary"><span class="fa fa-search"></span><span>Generate</span></button>
      <label style="display:none;" for="formButtonReset">Reset</label>
  		<button id="formButtonReset" class="formButton btn btn-primary"><span class="fa fa-undo"></span><span>Reset</span></button>
      <label style="display:none;" for="formButtonCsv">Export CSV</label>
  		<button id="formButtonCsv" class="formButton btn btn-primary"><span class="fa fa-floppy-o"></span><span>Export CSV</span></button>
      <label style="display:none;" for="formButtonPdf">Export PDF</label>
  		<button id="formButtonPdf" class="formButton btn btn-primary"><span class="fa fa-floppy-o"></span><span>Export PDF</span></button>
      <label style="display:none;" for="downloadcsv">Export CSV</label>
      <div id="downloadcsv" class="formButton formButtonSwf"></div>
      <label style="display:none;" for="downloadpdf">Export PDF</label>
      <div id="downloadpdf" class="formButton formButtonSwf"></div></form>
  	</div>
  </div>

</div>
<br />


<html><head>


<!-- Load require.js. Delete this if your page already loads require.js -->
<script src="https://cdnjs.cloudflare.com/ajax/libs/require.js/2.3.4/require.min.js" integrity="sha256-Ae2Vz/4ePdIu6ZyI/5ZGsYnb+m0JlOmKPjt6XZ9JJkA=" crossorigin="anonymous"></script>
<script src="https://unpkg.com/@jupyter-widgets/html-manager@*/dist/embed-amd.js" crossorigin="anonymous"></script>
<script type="application/vnd.jupyter.widget-state+json">
{
    "version_major": 2,
    "version_minor": 0,
    "state": {
        "001c21cced81437c813f2aa6cb441c81": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "OCC",
                    "FDIC",
                    "SEC",
                    "FHFA",
                    "CFTC"
                ],
                "description": "Regulator :",
                "index": 0,
                "layout": "IPY_MODEL_56e77ae1a15d406d83b3d477dce206b4",
                "style": "IPY_MODEL_4e636f5bfd604211a41306b4ff24fb83"
            }
        },
        "003ed765ba904837a7d2d3c902c4585f": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "005da8ed8a134839a15dbfa7de5775d7": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "009131b7555f4bf7975d3dd68ab5a2d0": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "0099551ae1a34d73aead39a1c06baee1": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "00a225c62edd4c62b761458374669ba3": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "00b44b962d4e4666ae43a5fd791038b9": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "00ec21931d1f401298f3f5ccf6cc38c0": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "00f6c426dfb34263aad4813b5b556ac4": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "Alabama",
                    "Arizona",
                    "Arkansas",
                    "California",
                    "Colorado",
                    "Connecticut",
                    "Delaware",
                    "District of Columbia",
                    "Florida",
                    "Georgia",
                    "Hawaii",
                    "Idaho",
                    "Illinois",
                    "Indiana",
                    "Iowa",
                    "Kansas",
                    "Kentucky",
                    "Louisiana",
                    "Maine",
                    "Maryland",
                    "Massachusetts",
                    "Michigan",
                    "Minnesota",
                    "Mississippi",
                    "Missouri",
                    "Montana",
                    "Nebraska",
                    "Nevada",
                    "New Hampshire",
                    "New Jersey",
                    "New Mexico",
                    "New York",
                    "North Carolina",
                    "North Dakota",
                    "Ohio",
                    "Oklahoma",
                    "Oregon",
                    "Pennsylvania",
                    "Puerto Rico",
                    "Rhode Island",
                    "South Carolina",
                    "South Dakota",
                    "Tennessee",
                    "Texas",
                    "Utah",
                    "Vermont",
                    "Virginia",
                    "Washington",
                    "West Virginia",
                    "Wisconsin"
                ],
                "description": "Filing State :",
                "index": 0,
                "layout": "IPY_MODEL_f40fe97b85a74ddc905b053b5456ab7b",
                "style": "IPY_MODEL_f9f79f117b724d3c8179ab0d5dc51321"
            }
        },
        "00f8015fc1e74bc49b5c38482d25f4d5": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "Alabama",
                    "Arizona",
                    "Arkansas",
                    "California",
                    "Colorado",
                    "Connecticut",
                    "Delaware",
                    "District of Columbia",
                    "Florida",
                    "Georgia",
                    "Hawaii",
                    "Idaho",
                    "Illinois",
                    "Indiana",
                    "Iowa",
                    "Kansas",
                    "Kentucky",
                    "Louisiana",
                    "Maine",
                    "Maryland",
                    "Massachusetts",
                    "Michigan",
                    "Minnesota",
                    "Mississippi",
                    "Missouri",
                    "Montana",
                    "Nebraska",
                    "Nevada",
                    "New Hampshire",
                    "New Jersey",
                    "New Mexico",
                    "New York",
                    "North Carolina",
                    "North Dakota",
                    "Ohio",
                    "Oklahoma",
                    "Oregon",
                    "Pennsylvania",
                    "Puerto Rico",
                    "Rhode Island",
                    "South Carolina",
                    "South Dakota",
                    "Tennessee",
                    "Texas",
                    "Utah",
                    "Vermont",
                    "Virginia",
                    "Washington",
                    "West Virginia",
                    "Wisconsin"
                ],
                "description": "Filing State :",
                "index": 0,
                "layout": "IPY_MODEL_67f42c2c4503455caca77ddb1c5aa138",
                "style": "IPY_MODEL_ea33a49fb1e749f88769aaf701821531"
            }
        },
        "00fb68967f224c329f306100bab324ce": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "00ff31413ff246939fcb61ec5c9ea41c": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "2014",
                    "2019",
                    "2015",
                    "2018",
                    "2017",
                    "2016",
                    "2012",
                    "2013"
                ],
                "description": "Date : ",
                "index": 1,
                "layout": "IPY_MODEL_7d1162be884040ebaf9f04f1b7414a07",
                "style": "IPY_MODEL_e12570447d364a32ac1a68b72bab42da"
            }
        },
        "01599ca60b4940b283c6e1bfc7cdc398": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "0160cf49eb0e4aa4a92844cbc3d9639b": {
            "model_name": "VBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_2c612d3dbcae44408fed451c23c77474",
                    "IPY_MODEL_0208ac30f4884f779ffaab513bc1adfe",
                    "IPY_MODEL_01a5ab497cc84c97b986b7df36d1f798"
                ],
                "layout": "IPY_MODEL_74cd2f706d49426ab34db595db04415b"
            }
        },
        "01a5ab497cc84c97b986b7df36d1f798": {
            "model_name": "FigureModel",
            "model_module": "plotlywidget",
            "model_module_version": "0.9.1",
            "state": {
                "_config": {
                    "plotlyServerURL": "https://plot.ly"
                },
                "_data": [
                    {
                        "marker": {
                            "color": "rgb(26, 118, 255)",
                            "line": {
                                "color": "rgba(100, 10, 205, 1.0)",
                                "width": 2
                            }
                        },
                        "orientation": "v",
                        "type": "bar",
                        "uid": "bfb8b6d6-f7a7-49ab-8175-6d556dd23bba",
                        "x": [
                            "Credit Card",
                            "Debit Card",
                            "Deposit Account",
                            "Forex Transactions",
                            "Mutual Fund",
                            "Residential Mortgage"
                        ],
                        "y": [
                            2125,
                            17173,
                            35680,
                            89,
                            106,
                            257
                        ]
                    }
                ],
                "_js2py_restyle": {},
                "_js2py_update": {},
                "_last_layout_edit_id": 2,
                "_last_trace_edit_id": 1,
                "_layout": {
                    "annotations": [
                        {
                            "font": {
                                "color": "red",
                                "size": 10
                            },
                            "showarrow": false,
                            "text": "Source: FINCEN.gov",
                            "x": 1,
                            "xanchor": "right",
                            "xref": "paper",
                            "xshift": 0,
                            "y": -0.15,
                            "yanchor": "auto",
                            "yref": "paper",
                            "yshift": 0
                        }
                    ],
                    "autosize": true,
                    "barmode": "group",
                    "hovermode": "closest",
                    "paper_bgcolor": "whitesmoke",
                    "plot_bgcolor": "whitesmoke",
                    "template": {},
                    "title": {
                        "text": "SAR Filings by State and Product"
                    },
                    "xaxis": {
                        "title": {
                            "text": "SARs Filing Type"
                        }
                    },
                    "yaxis": {
                        "title": {
                            "text": "Number of Filings"
                        }
                    }
                },
                "_model_module_version": "0.9.1",
                "_py2js_addTraces": {},
                "_py2js_animate": {},
                "_py2js_deleteTraces": {},
                "_py2js_moveTraces": {},
                "_py2js_removeLayoutProps": {},
                "_py2js_removeTraceProps": {},
                "_py2js_restyle": {},
                "_view_count": 0,
                "_view_module_version": "0.9.1"
            }
        },
        "0208ac30f4884f779ffaab513bc1adfe": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_5603ee1a991442b29f12dd4427bee223",
                    "IPY_MODEL_6d864cc0141649e884700bd5292cde90"
                ],
                "layout": "IPY_MODEL_92f1aafedf034fbfb9170f8ae092eb79"
            }
        },
        "02169c8bda3340e2af4a137e7738e66f": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "2014",
                    "2019",
                    "2015",
                    "2018",
                    "2017",
                    "2016",
                    "2012",
                    "2013"
                ],
                "description": "Date : ",
                "index": 1,
                "layout": "IPY_MODEL_9fdf0cc6061d4b77a15b961ba360604b",
                "style": "IPY_MODEL_21d09342c00946a38f491837769c851e"
            }
        },
        "02472ded8bb149bfbbd665bc504d5e52": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "0311b4e7262e4332b391555ede1008a8": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "032337b9baf349809dce88a4262ca19f": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "032c9ef3ad6748109af8c122bea84998": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "03a401d7df404bfaaafdd48a88370492": {
            "model_name": "FigureModel",
            "model_module": "plotlywidget",
            "model_module_version": "0.9.1",
            "state": {
                "_config": {
                    "plotlyServerURL": "https://plot.ly"
                },
                "_data": [
                    {
                        "marker": {
                            "color": "rgb(26, 118, 255)",
                            "line": {
                                "color": "rgba(100, 120, 255, 1.0)",
                                "width": 2
                            }
                        },
                        "orientation": "v",
                        "type": "bar",
                        "uid": "91f436d7-e69c-4855-b0df-d279b7c0415b",
                        "x": [
                            "Debit Card",
                            "Deposit Account"
                        ],
                        "y": [
                            223,
                            493
                        ]
                    }
                ],
                "_js2py_restyle": {},
                "_js2py_update": {},
                "_last_layout_edit_id": 1,
                "_layout": {
                    "annotations": [
                        {
                            "font": {
                                "color": "red",
                                "size": 10
                            },
                            "showarrow": false,
                            "text": "Source: FINCEN.gov",
                            "x": 1,
                            "xanchor": "right",
                            "xref": "paper",
                            "xshift": 0,
                            "y": -0.15,
                            "yanchor": "auto",
                            "yref": "paper",
                            "yshift": 0
                        }
                    ],
                    "autosize": true,
                    "barmode": "group",
                    "hovermode": "closest",
                    "template": {},
                    "title": {
                        "text": "SAR Filings by State and Product"
                    }
                },
                "_model_module_version": "0.9.1",
                "_py2js_addTraces": {},
                "_py2js_animate": {},
                "_py2js_deleteTraces": {},
                "_py2js_moveTraces": {},
                "_py2js_removeLayoutProps": {},
                "_py2js_removeTraceProps": {},
                "_py2js_restyle": {},
                "_py2js_update": {},
                "_view_count": 0,
                "_view_module_version": "0.9.1"
            }
        },
        "03adc70976a94d9aa9df49c4222f553b": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "03daae0cfbd746e0812917dae1e78cae": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "0427a4a741034461bbdf20fd0def9d0a": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "2014",
                    "2019",
                    "2015",
                    "2018",
                    "2017",
                    "2016",
                    "2012",
                    "2013"
                ],
                "description": "Date : ",
                "index": 1,
                "layout": "IPY_MODEL_8e5d7cd162c94119864516d98e3191f4",
                "style": "IPY_MODEL_f923f3895c05403894d80347b7dfb99e"
            }
        },
        "04436bbc1b184d22ab0440826ec590f4": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "04fa5773b6ae473fb1241bfe1363f010": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "2014",
                    "2019",
                    "2015",
                    "2018",
                    "2017",
                    "2016",
                    "2012",
                    "2013"
                ],
                "description": "Date : ",
                "index": 1,
                "layout": "IPY_MODEL_3b3de6fa5b19437f8c640de8b9ded12e",
                "style": "IPY_MODEL_23cf7bcc22924127b35d277ace132e67"
            }
        },
        "050537fbad4e4afaaa115c080ebd3648": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_cebd8f6c29db4f13b4095609bc32912a"
                ],
                "layout": "IPY_MODEL_68e3de60ae0d400db88062a58e7c2b28"
            }
        },
        "051ea114b2944a2580f47fde91d8259b": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "055a884974684d4baba6294cdf332605": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "OCC",
                    "FDIC",
                    "SEC",
                    "FHFA",
                    "CFTC"
                ],
                "description": "Regulator :",
                "index": 0,
                "layout": "IPY_MODEL_c4a7b106caf24623a3c9e8d805af4e3e",
                "style": "IPY_MODEL_5bb5e4da0a954ce894403affdf943c9f"
            }
        },
        "05bc6ffa06a24f1fbb606afd425eae35": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "05c9d9d301d245fcb752e20819eb473c": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "05fd9b45ec5943a2937a5a5bf8a77708": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "060480c31f384661997b4aed2806ff14": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "OCC",
                    "FDIC",
                    "SEC",
                    "FHFA",
                    "CFTC"
                ],
                "description": "Regulator :",
                "index": 0,
                "layout": "IPY_MODEL_26046907afe24777ba989a8a18fc2ff1",
                "style": "IPY_MODEL_92654ec1cd654c7a80cfe787f4a61a53"
            }
        },
        "06129b1c6243459d9e6a9fa5bdc020e1": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "2014",
                    "2019",
                    "2015",
                    "2018",
                    "2017",
                    "2016",
                    "2012",
                    "2013"
                ],
                "description": "Date : ",
                "index": 1,
                "layout": "IPY_MODEL_7af8fb890cb24e2eae582d1d3eda520e",
                "style": "IPY_MODEL_fcc6da6d479f40e78e3fc03021cd82fe"
            }
        },
        "06225ad1facd41cbacbf5280a62cf5f0": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "069bc514931749048b2f9f6444cb7b55": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "06b022b61b7546cd963dd2730928cf91": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "06fe23c2cdde486b9e8209f949986c34": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "0718b9923202492894b2cd94f88008d0": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "0727a5c642304646b983f9c96d15e4dc": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "074b7b8ee4c24962b3abbfb56c442481": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "0754e8becfa14e14bbc4cff147b3910f": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "2014",
                    "2019",
                    "2015",
                    "2018",
                    "2017",
                    "2016",
                    "2012",
                    "2013"
                ],
                "description": "Date : ",
                "index": 1,
                "layout": "IPY_MODEL_593718dda83e4600b1e582e6d18792bb",
                "style": "IPY_MODEL_0fb34d83c5a34d29907e7bba0367b28f"
            }
        },
        "07729b2cc35c477bbda2631d40709767": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "07a86387e3a54a1cae4b0e9fdb7c7582": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "2014",
                    "2019",
                    "2015",
                    "2018",
                    "2017",
                    "2016",
                    "2012",
                    "2013"
                ],
                "description": "Date : ",
                "index": 1,
                "layout": "IPY_MODEL_ac7b2a3bf249489698b89fede6da4be8",
                "style": "IPY_MODEL_3b3d77574e5e4870b89662cab647c13b"
            }
        },
        "07b45612595f46299827d78ce1d23b5a": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "OCC",
                    "FDIC",
                    "SEC",
                    "FHFA",
                    "CFTC"
                ],
                "description": "Regulator :",
                "index": 0,
                "layout": "IPY_MODEL_842866ccb7744a329ec42e766c0c922b",
                "style": "IPY_MODEL_07ec5548246b4d5ab63ac4e7afd8654c"
            }
        },
        "07b48e1fec1040849bc8c4b264fc60b5": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "07be55243fdf46b4870fc72e90d8c8fc": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "07ec5548246b4d5ab63ac4e7afd8654c": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "080005fb6b374432aa280a83aa9c72c2": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "OCC",
                    "FDIC",
                    "SEC",
                    "FHFA",
                    "CFTC"
                ],
                "description": "Regulator :",
                "index": 0,
                "layout": "IPY_MODEL_b4fb4491b9c245178979d9b6bce95abe",
                "style": "IPY_MODEL_f1b81fd9bd8045778faeee68d38822d0"
            }
        },
        "0809cba7295041fe96a00a52e2ab26b9": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "0826016a2aac4baea461c7810d21be6f": {
            "model_name": "VBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_84f8e4dc449545c798f1102228e7eb98",
                    "IPY_MODEL_fb04684418c549ada29ecfe773c13daa",
                    "IPY_MODEL_9e0f47d7abf74088824e918a9e9ac939"
                ],
                "layout": "IPY_MODEL_839db55304ac487db749819fda7ba093"
            }
        },
        "0863977cd8b743a788586b6159feaee3": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "08fc92471463413495150a9c1047262f": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "2014",
                    "2019",
                    "2015",
                    "2018",
                    "2017",
                    "2016",
                    "2012",
                    "2013"
                ],
                "description": "Date : ",
                "index": 1,
                "layout": "IPY_MODEL_10ea314339a64b83a28054eb1947fcb2",
                "style": "IPY_MODEL_05fd9b45ec5943a2937a5a5bf8a77708"
            }
        },
        "09133e00e34843b5beb50fdfe9032995": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "091747c504d24ee69dca82fba9823216": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_c9db6fc0270e4b9ca1e0f48e02b30ca4"
                ],
                "layout": "IPY_MODEL_6720438d3f514a198be600412fc70395"
            }
        },
        "09180af1f2124239aa6f0dd43a4d8ecd": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "091b84c92e774dd58bdfc7f315f7af9a": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_a63fd57cea674e4984eb320d260178f1"
                ],
                "layout": "IPY_MODEL_da0f3a46959d4910b3b7309d06d393c2"
            }
        },
        "0991ca0e4efc46148f92454a06b833e9": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "09baa9befb82457a9372eae87b863bdd": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "0a5338114e824313b5dd8a142ea87f35": {
            "model_name": "FigureModel",
            "model_module": "plotlywidget",
            "model_module_version": "0.9.1",
            "state": {
                "_config": {
                    "plotlyServerURL": "https://plot.ly"
                },
                "_data": [
                    {
                        "marker": {
                            "color": "rgb(26, 118, 255)"
                        },
                        "orientation": "v",
                        "type": "bar",
                        "uid": "1f67c1d1-71b4-4321-95ce-b449b0a2461d",
                        "x": [
                            "Debit Card",
                            "Deposit Account"
                        ],
                        "y": [
                            223,
                            493
                        ]
                    }
                ],
                "_js2py_pointsCallback": {},
                "_js2py_restyle": {},
                "_js2py_update": {},
                "_last_layout_edit_id": 1,
                "_layout": {
                    "annotations": [
                        {
                            "font": {
                                "color": "red",
                                "size": 10
                            },
                            "showarrow": false,
                            "text": "Source: FINCEN.gov",
                            "x": 1,
                            "xanchor": "right",
                            "xref": "paper",
                            "xshift": 0,
                            "y": -0.15,
                            "yanchor": "auto",
                            "yref": "paper",
                            "yshift": 0
                        }
                    ],
                    "autosize": true,
                    "barmode": "group",
                    "hovermode": "closest",
                    "template": {},
                    "title": {
                        "text": "SAR Filings by State and Product"
                    }
                },
                "_model_module_version": "0.9.1",
                "_py2js_addTraces": {},
                "_py2js_animate": {},
                "_py2js_deleteTraces": {},
                "_py2js_moveTraces": {},
                "_py2js_removeLayoutProps": {},
                "_py2js_removeTraceProps": {},
                "_py2js_restyle": {},
                "_py2js_update": {},
                "_view_count": 0,
                "_view_module_version": "0.9.1"
            }
        },
        "0a546ca655034c27b380776df37326a0": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "0ab038dfe46c4f77acffd5fff017922d": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "0ac126afbc16447fb6bd64d22e241157": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_76d0d27363f0409aa1e29c7694d17d86"
                ],
                "layout": "IPY_MODEL_369d01035d584ee08a84c09fe23de0bc"
            }
        },
        "0aec0ab592f84dffa24e052db6414d44": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_ac890c2f7af54efe8d3693b9e459c944",
                    "IPY_MODEL_e617716cb79a49588e3940b8090f5bed"
                ],
                "layout": "IPY_MODEL_ea2dd84a06d245a5a346f4a4d7cf6f20"
            }
        },
        "0b25ee1d8b394e83af443d04b7a8235b": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_86034c0904c64e73a7cca576f59efee2",
                    "IPY_MODEL_9117c01a7e0947469410d6f4eb2bd783"
                ],
                "layout": "IPY_MODEL_32ddd6272af2480a8ef0a5c112dfac21"
            }
        },
        "0b4bc8892f2845bfbff9bc663236cdea": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "0bafc20d0d164a1c9d1b83a8fa6b6f9e": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "0bdcbfbee39c484fbd36bd50b990c693": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "0c00b72d36ce4a81a2903d4454f7800f": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "Alabama",
                    "Arizona",
                    "Arkansas",
                    "California",
                    "Colorado",
                    "Connecticut",
                    "Delaware",
                    "District of Columbia",
                    "Florida",
                    "Georgia",
                    "Hawaii",
                    "Idaho",
                    "Illinois",
                    "Indiana",
                    "Iowa",
                    "Kansas",
                    "Kentucky",
                    "Louisiana",
                    "Maine",
                    "Maryland",
                    "Massachusetts",
                    "Michigan",
                    "Minnesota",
                    "Mississippi",
                    "Missouri",
                    "Montana",
                    "Nebraska",
                    "Nevada",
                    "New Hampshire",
                    "New Jersey",
                    "New Mexico",
                    "New York",
                    "North Carolina",
                    "North Dakota",
                    "Ohio",
                    "Oklahoma",
                    "Oregon",
                    "Pennsylvania",
                    "Puerto Rico",
                    "Rhode Island",
                    "South Carolina",
                    "South Dakota",
                    "Tennessee",
                    "Texas",
                    "Utah",
                    "Vermont",
                    "Virginia",
                    "Washington",
                    "West Virginia",
                    "Wisconsin"
                ],
                "description": "Filing State :",
                "index": 0,
                "layout": "IPY_MODEL_3bbea1f47e494769891c6f3457133451",
                "style": "IPY_MODEL_f2f2760c656644d08be8d3030661adc9"
            }
        },
        "0c36a883892f4170a560b00255bee453": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "Alabama",
                    "Arizona",
                    "Arkansas",
                    "California",
                    "Colorado",
                    "Connecticut",
                    "Delaware",
                    "District of Columbia",
                    "Florida",
                    "Georgia",
                    "Hawaii",
                    "Idaho",
                    "Illinois",
                    "Indiana",
                    "Iowa",
                    "Kansas",
                    "Kentucky",
                    "Louisiana",
                    "Maine",
                    "Maryland",
                    "Massachusetts",
                    "Michigan",
                    "Minnesota",
                    "Mississippi",
                    "Missouri",
                    "Montana",
                    "Nebraska",
                    "Nevada",
                    "New Hampshire",
                    "New Jersey",
                    "New Mexico",
                    "New York",
                    "North Carolina",
                    "North Dakota",
                    "Ohio",
                    "Oklahoma",
                    "Oregon",
                    "Pennsylvania",
                    "Puerto Rico",
                    "Rhode Island",
                    "South Carolina",
                    "South Dakota",
                    "Tennessee",
                    "Texas",
                    "Utah",
                    "Vermont",
                    "Virginia",
                    "Washington",
                    "West Virginia",
                    "Wisconsin"
                ],
                "description": "Filing State :",
                "index": 0,
                "layout": "IPY_MODEL_18f7e0c5e41847a2bc670171d2fdc0d4",
                "style": "IPY_MODEL_0863977cd8b743a788586b6159feaee3"
            }
        },
        "0c3c5ab3574a4a76b8678973cfeec8f8": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "0cb46a90a98d4a5ca7108851d185d7c6": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_ae71c2e4b30845a9a2d285169a1b4e56"
                ],
                "layout": "IPY_MODEL_b6d25c5801a648d1bf0edce30619b4f2"
            }
        },
        "0d1d7ebc318b4943a0f7d8c75e9d8f04": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "0d440d4e3640489094c2b70d9678f146": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "0dba18924f9e482998e714de7282a2fe": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "0df7a4c858d34b01960454d84726f45e": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "0e19c738104648dca165e98c9188a201": {
            "model_name": "FigureModel",
            "model_module": "plotlywidget",
            "model_module_version": "0.9.1",
            "state": {
                "_config": {
                    "plotlyServerURL": "https://plot.ly"
                },
                "_data": [
                    {
                        "marker": {
                            "color": "rgb(26, 118, 255)",
                            "line": {
                                "color": "rgba(100, 10, 205, 1.0)",
                                "width": 2
                            }
                        },
                        "orientation": "v",
                        "type": "bar",
                        "uid": "f61221be-430b-429a-9235-48013254aa23",
                        "x": [
                            "Debit Card",
                            "Deposit Account"
                        ],
                        "y": [
                            223,
                            493
                        ]
                    }
                ],
                "_js2py_pointsCallback": {},
                "_js2py_restyle": {},
                "_js2py_update": {},
                "_last_layout_edit_id": 1,
                "_layout": {
                    "annotations": [
                        {
                            "font": {
                                "color": "red",
                                "size": 10
                            },
                            "showarrow": false,
                            "text": "Source: FINCEN.gov",
                            "x": 1,
                            "xanchor": "right",
                            "xref": "paper",
                            "xshift": 0,
                            "y": -0.15,
                            "yanchor": "auto",
                            "yref": "paper",
                            "yshift": 0
                        }
                    ],
                    "autosize": true,
                    "barmode": "group",
                    "hovermode": "closest",
                    "paper_bgcolor": "whitesmoke",
                    "plot_bgcolor": "whitesmoke",
                    "shapes": [
                        {
                            "line": {
                                "color": "RoyalBlue"
                            },
                            "type": "rect",
                            "x0": 0,
                            "x1": 0,
                            "y0": 0,
                            "y1": 0
                        }
                    ],
                    "template": {},
                    "title": {
                        "text": "Number SAR Filings by State and Product\n(Filings Greater than 80)"
                    }
                },
                "_model_module_version": "0.9.1",
                "_py2js_addTraces": {},
                "_py2js_animate": {},
                "_py2js_deleteTraces": {},
                "_py2js_moveTraces": {},
                "_py2js_removeLayoutProps": {},
                "_py2js_removeTraceProps": {},
                "_py2js_restyle": {},
                "_py2js_update": {},
                "_view_count": 0,
                "_view_module_version": "0.9.1"
            }
        },
        "0e3c61bc4f194d98961ae09c9b698e90": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "0e59c55f213047119f553986b3ef2f6a": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "2014",
                    "2019",
                    "2015",
                    "2018",
                    "2017",
                    "2016",
                    "2012",
                    "2013"
                ],
                "description": "Date : ",
                "index": 1,
                "layout": "IPY_MODEL_5b0b1cb3599f4d8e824cf0a922906caf",
                "style": "IPY_MODEL_cbdadc53f0ef4c749a99f7721c935013"
            }
        },
        "0e634793da0a458690e9edce4f4f4418": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "0ea9ecccde064d39be23980e7e5e7da7": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "2014",
                    "2019",
                    "2015",
                    "2018",
                    "2017",
                    "2016",
                    "2012",
                    "2013"
                ],
                "description": "Date : ",
                "index": 1,
                "layout": "IPY_MODEL_8e5b097af95c42a89243592f70d859ed",
                "style": "IPY_MODEL_f6e84cc88dfc4418a0e785e042ecdff9"
            }
        },
        "0f231e76d3f941c89e22df5a0a87dfe4": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "0f304f11b2514d69b5ca2b5cd73e5862": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "0fa2f5a67c7b4bac9b33fd053c71dc0a": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "Alabama",
                    "Arizona",
                    "Arkansas",
                    "California",
                    "Colorado",
                    "Connecticut",
                    "Delaware",
                    "District of Columbia",
                    "Florida",
                    "Georgia",
                    "Hawaii",
                    "Idaho",
                    "Illinois",
                    "Indiana",
                    "Iowa",
                    "Kansas",
                    "Kentucky",
                    "Louisiana",
                    "Maine",
                    "Maryland",
                    "Massachusetts",
                    "Michigan",
                    "Minnesota",
                    "Mississippi",
                    "Missouri",
                    "Montana",
                    "Nebraska",
                    "Nevada",
                    "New Hampshire",
                    "New Jersey",
                    "New Mexico",
                    "New York",
                    "North Carolina",
                    "North Dakota",
                    "Ohio",
                    "Oklahoma",
                    "Oregon",
                    "Pennsylvania",
                    "Puerto Rico",
                    "Rhode Island",
                    "South Carolina",
                    "South Dakota",
                    "Tennessee",
                    "Texas",
                    "Utah",
                    "Vermont",
                    "Virginia",
                    "Washington",
                    "West Virginia",
                    "Wisconsin"
                ],
                "description": "Filing State :",
                "index": 0,
                "layout": "IPY_MODEL_6a9ae312b2ab4c51a2db082f05086867",
                "style": "IPY_MODEL_4c6066165991458f9d86ba3a3a8c75e6"
            }
        },
        "0fb34d83c5a34d29907e7bba0367b28f": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "0fb6d6226ad44ef88934aad5d29fc1b2": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "Alabama",
                    "Arizona",
                    "Arkansas",
                    "California",
                    "Colorado",
                    "Connecticut",
                    "Delaware",
                    "District of Columbia",
                    "Florida",
                    "Georgia",
                    "Hawaii",
                    "Idaho",
                    "Illinois",
                    "Indiana",
                    "Iowa",
                    "Kansas",
                    "Kentucky",
                    "Louisiana",
                    "Maine",
                    "Maryland",
                    "Massachusetts",
                    "Michigan",
                    "Minnesota",
                    "Mississippi",
                    "Missouri",
                    "Montana",
                    "Nebraska",
                    "Nevada",
                    "New Hampshire",
                    "New Jersey",
                    "New Mexico",
                    "New York",
                    "North Carolina",
                    "North Dakota",
                    "Ohio",
                    "Oklahoma",
                    "Oregon",
                    "Pennsylvania",
                    "Puerto Rico",
                    "Rhode Island",
                    "South Carolina",
                    "South Dakota",
                    "Tennessee",
                    "Texas",
                    "Utah",
                    "Vermont",
                    "Virginia",
                    "Washington",
                    "West Virginia",
                    "Wisconsin"
                ],
                "description": "Filing State :",
                "index": 0,
                "layout": "IPY_MODEL_bc81ec7d8d4c4234902e17db7f9fc08f",
                "style": "IPY_MODEL_1dbff8766f63488789de68ff8e89e677"
            }
        },
        "0fde65214bec46df899733f73fff32ee": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "101f2120c5cc44a685ba83cbbbe7b981": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "1038583425e84af5a93f38934f77ca38": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "OCC",
                    "FDIC",
                    "SEC",
                    "FHFA",
                    "CFTC"
                ],
                "description": "Regulator :",
                "index": 0,
                "layout": "IPY_MODEL_4a3b2cea94684b68a331a52a504d32cd",
                "style": "IPY_MODEL_ffcb967e5e064243ad92790e565a6d6b"
            }
        },
        "106c99bd961e448991d8d896072d0b86": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "1076af3152fd400684dcf83c7bdb1aea": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "10b440af36e04762925c6cc594880b68": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "10ea314339a64b83a28054eb1947fcb2": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "10fc913a807640aa92d10f38a8a76e8f": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "111339e3a67f4100b49f153f5a912f88": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "1128511b3e48472fadbe33abfd1f12b5": {
            "model_name": "FigureModel",
            "model_module": "plotlywidget",
            "model_module_version": "0.9.1",
            "state": {
                "_config": {
                    "plotlyServerURL": "https://plot.ly"
                },
                "_data": [
                    {
                        "marker": {
                            "color": "rgb(26, 118, 255)",
                            "line": {
                                "color": "rgba(100, 10, 205, 1.0)",
                                "width": 2
                            }
                        },
                        "orientation": "v",
                        "type": "bar",
                        "uid": "bd073e5b-0df5-4e8a-815d-d3c41cef3beb",
                        "x": [
                            "Debit Card",
                            "Deposit Account"
                        ],
                        "y": [
                            223,
                            493
                        ]
                    }
                ],
                "_js2py_pointsCallback": {},
                "_js2py_restyle": {},
                "_js2py_update": {},
                "_last_layout_edit_id": 1,
                "_layout": {
                    "annotations": [
                        {
                            "font": {
                                "color": "red",
                                "size": 10
                            },
                            "showarrow": false,
                            "text": "Source: FINCEN.gov",
                            "x": 1,
                            "xanchor": "right",
                            "xref": "paper",
                            "xshift": 0,
                            "y": -0.15,
                            "yanchor": "auto",
                            "yref": "paper",
                            "yshift": 0
                        }
                    ],
                    "autosize": true,
                    "barmode": "group",
                    "hovermode": "closest",
                    "plot_bgcolor": "light green",
                    "template": {},
                    "title": {
                        "text": "SAR Filings by State and Product"
                    }
                },
                "_model_module_version": "0.9.1",
                "_py2js_addTraces": {},
                "_py2js_animate": {},
                "_py2js_deleteTraces": {},
                "_py2js_moveTraces": {},
                "_py2js_removeLayoutProps": {},
                "_py2js_removeTraceProps": {},
                "_py2js_restyle": {},
                "_py2js_update": {},
                "_view_count": 0,
                "_view_module_version": "0.9.1"
            }
        },
        "113ce5f7e51e450096855924e592b467": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "1150476c774e4a0e80bfba722cb7d09b": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "11883eb4dacc436a9f0bc259930df6b2": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "119289f9d05e4e15b0ade113b08b7979": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "11a5de5a7673472091ee8344eae217c5": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "2014",
                    "2019",
                    "2015",
                    "2018",
                    "2017",
                    "2016",
                    "2012",
                    "2013"
                ],
                "description": "Date : ",
                "index": 1,
                "layout": "IPY_MODEL_3b40896889564991a21e058ecc1e3665",
                "style": "IPY_MODEL_128de82689e7446381947be040df059b"
            }
        },
        "11ec603d78ec4afb8a6fc58504fb839f": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "11f91d4e059647b393cb1880c33f1ef6": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "12068c9f595347deb0c3e31dcfed9d81": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "120d9d0e290048369a2fb154b6b569d8": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "123025abddcf427a887ed1776849e013": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "12302c1eba774d48b1fa18a666739d08": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "1234f759d0314d64b6730512ea26cbc6": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "123d376adb964e60af116b3c84ec8615": {
            "model_name": "VBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_347bdb2cdc564b29a3c676ab4a8ad714",
                    "IPY_MODEL_db8244c9e8944293a7f0c91ed1f261e9",
                    "IPY_MODEL_644009bd949249c089175d25d01f9d21"
                ],
                "layout": "IPY_MODEL_9d202069215e453699038f374144d0ad"
            }
        },
        "128d4169c3704625a78309303d9e9d87": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "128de82689e7446381947be040df059b": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "1299016b3a5c481d9108c84a832b9d86": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_ba57371a22004a818b5fa643069ef1da"
                ],
                "layout": "IPY_MODEL_f662763a753a44a88849709613031b7e"
            }
        },
        "12c576eaf6854f02a43b8aba021151d5": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "132102aa69f649deb65ecd4e67286bdf": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "2014",
                    "2019",
                    "2015",
                    "2018",
                    "2017",
                    "2016",
                    "2012",
                    "2013"
                ],
                "description": "Date : ",
                "index": 1,
                "layout": "IPY_MODEL_b6a3e85cd10145feadb1f85e47281248",
                "style": "IPY_MODEL_627da2c7c79d42219c6c472548030643"
            }
        },
        "132a475153ba4b1ba75418b69863679c": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "Alabama",
                    "Arizona",
                    "Arkansas",
                    "California",
                    "Colorado",
                    "Connecticut",
                    "Delaware",
                    "District of Columbia",
                    "Florida",
                    "Georgia",
                    "Hawaii",
                    "Idaho",
                    "Illinois",
                    "Indiana",
                    "Iowa",
                    "Kansas",
                    "Kentucky",
                    "Louisiana",
                    "Maine",
                    "Maryland",
                    "Massachusetts",
                    "Michigan",
                    "Minnesota",
                    "Mississippi",
                    "Missouri",
                    "Montana",
                    "Nebraska",
                    "Nevada",
                    "New Hampshire",
                    "New Jersey",
                    "New Mexico",
                    "New York",
                    "North Carolina",
                    "North Dakota",
                    "Ohio",
                    "Oklahoma",
                    "Oregon",
                    "Pennsylvania",
                    "Puerto Rico",
                    "Rhode Island",
                    "South Carolina",
                    "South Dakota",
                    "Tennessee",
                    "Texas",
                    "Utah",
                    "Vermont",
                    "Virginia",
                    "Washington",
                    "West Virginia",
                    "Wisconsin"
                ],
                "description": "Filing State :",
                "index": 0,
                "layout": "IPY_MODEL_be529f39366c4a4f9efc2b0f0121ba1f",
                "style": "IPY_MODEL_72e754996ebc4fcfa6db9009c606391f"
            }
        },
        "134e8ca884d64d3cac0e9ecc37cb2f39": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "OCC",
                    "FDIC",
                    "SEC",
                    "FHFA",
                    "CFTC"
                ],
                "description": "Regulator :",
                "index": 0,
                "layout": "IPY_MODEL_6b1adc502fa544708a82e5675e6c8ca3",
                "style": "IPY_MODEL_c689aa261a374bac9172dbadb3663b78"
            }
        },
        "1357cc7b545644efb89e0a8c1b099a45": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "Alabama",
                    "Arizona",
                    "Arkansas",
                    "California",
                    "Colorado",
                    "Connecticut",
                    "Delaware",
                    "District of Columbia",
                    "Florida",
                    "Georgia",
                    "Hawaii",
                    "Idaho",
                    "Illinois",
                    "Indiana",
                    "Iowa",
                    "Kansas",
                    "Kentucky",
                    "Louisiana",
                    "Maine",
                    "Maryland",
                    "Massachusetts",
                    "Michigan",
                    "Minnesota",
                    "Mississippi",
                    "Missouri",
                    "Montana",
                    "Nebraska",
                    "Nevada",
                    "New Hampshire",
                    "New Jersey",
                    "New Mexico",
                    "New York",
                    "North Carolina",
                    "North Dakota",
                    "Ohio",
                    "Oklahoma",
                    "Oregon",
                    "Pennsylvania",
                    "Puerto Rico",
                    "Rhode Island",
                    "South Carolina",
                    "South Dakota",
                    "Tennessee",
                    "Texas",
                    "Utah",
                    "Vermont",
                    "Virginia",
                    "Washington",
                    "West Virginia",
                    "Wisconsin"
                ],
                "description": "Filing State :",
                "index": 0,
                "layout": "IPY_MODEL_78acd5cbbc4a4a5ead67f70b1c332d44",
                "style": "IPY_MODEL_6bbc773a0f034f7a9a6e2b6f2c38fb1a"
            }
        },
        "13c692d834694c948c099a87657534c3": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "13d890a5a18d4c098081528aa7913786": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "2014",
                    "2019",
                    "2015",
                    "2018",
                    "2017",
                    "2016",
                    "2012",
                    "2013"
                ],
                "description": "Date : ",
                "index": 1,
                "layout": "IPY_MODEL_8a4a53b371db4f51ac4a6f9b743cff03",
                "style": "IPY_MODEL_7a30e99dc8274f9db7c2a5b088407819"
            }
        },
        "13f2910d9cdb4d1daadac8dd6ed2a28c": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "1417e2e28491443b9b8fe96b35ac6412": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "2014",
                    "2019",
                    "2015",
                    "2018",
                    "2017",
                    "2016",
                    "2012",
                    "2013"
                ],
                "description": "Date : ",
                "index": 1,
                "layout": "IPY_MODEL_f5bd69d130874d19a54e4c2bbeba9f9a",
                "style": "IPY_MODEL_5f3a944128a345caae5388d5f6c2174f"
            }
        },
        "141b448174f34d9ca47f30ec13997980": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "OCC",
                    "FDIC",
                    "SEC",
                    "FHFA",
                    "CFTC"
                ],
                "description": "Regulator :",
                "index": 0,
                "layout": "IPY_MODEL_80da466e9f434350a2e27ecc4cb69840",
                "style": "IPY_MODEL_0bafc20d0d164a1c9d1b83a8fa6b6f9e"
            }
        },
        "14808ad46f04413eb5f7622a15cfd133": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "148bf5a2afbc4c4d9808b6f702e4963a": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "14b8bfd6ca08440e8d16a9b722d1407f": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_20a15a5684aa4f9a81806537b058f84e"
                ],
                "layout": "IPY_MODEL_1b216dfe9f7140759f7e4e6d6cadcfbf"
            }
        },
        "14d96d28a7de4386aa9a9e9deb8ee60c": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_ce78c402853a49d0aba1af32ded00126"
                ],
                "layout": "IPY_MODEL_959ee28cc65c4063a4d5c9ff420d8204"
            }
        },
        "14e24057ddd44f34800c06bdb3659a80": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "14edc24df1774b44985cbc07886f9e8f": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "15073740281942699c0635c349476035": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "1593f5bb557b4732b76ce000ee1e0072": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "OCC",
                    "FDIC",
                    "SEC",
                    "FHFA",
                    "CFTC"
                ],
                "description": "Regulator :",
                "index": 0,
                "layout": "IPY_MODEL_eecbd58379954402ba7537cff5c7f9d2",
                "style": "IPY_MODEL_3bce96798f7a4d29b7f90b0cb3bced09"
            }
        },
        "159a0ad5734f40bebae3f197eecd2d64": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_deb98c2193d047ed9ce0260f5050c294"
                ],
                "layout": "IPY_MODEL_bab4621820694459bff601dfb26f1ace"
            }
        },
        "159eb0a2eb6f49b78f8122728c3aea94": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "OCC",
                    "FDIC",
                    "SEC",
                    "FHFA",
                    "CFTC"
                ],
                "description": "Regulator :",
                "index": 0,
                "layout": "IPY_MODEL_cc78def55bd54bbf89d95928b2a58d17",
                "style": "IPY_MODEL_e66463cfe2004ff593e72f1838d29809"
            }
        },
        "15fde3171799480abb66f4afe309beec": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_ef94baa096a340ceab79bf6920c7b572"
                ],
                "layout": "IPY_MODEL_ae5c3f354b824a7d82752c0e20953a6c"
            }
        },
        "162ff54cd73a4f3fbdaecc6610791dbc": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "OCC",
                    "FDIC",
                    "SEC",
                    "FHFA",
                    "CFTC"
                ],
                "description": "Regulator :",
                "index": 0,
                "layout": "IPY_MODEL_005da8ed8a134839a15dbfa7de5775d7",
                "style": "IPY_MODEL_47a3eff975c84dee8bebf1802655a793"
            }
        },
        "1677bf48a0e044678404a6136d9a1082": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "Alabama",
                    "Arizona",
                    "Arkansas",
                    "California",
                    "Colorado",
                    "Connecticut",
                    "Delaware",
                    "District of Columbia",
                    "Florida",
                    "Georgia",
                    "Hawaii",
                    "Idaho",
                    "Illinois",
                    "Indiana",
                    "Iowa",
                    "Kansas",
                    "Kentucky",
                    "Louisiana",
                    "Maine",
                    "Maryland",
                    "Massachusetts",
                    "Michigan",
                    "Minnesota",
                    "Mississippi",
                    "Missouri",
                    "Montana",
                    "Nebraska",
                    "Nevada",
                    "New Hampshire",
                    "New Jersey",
                    "New Mexico",
                    "New York",
                    "North Carolina",
                    "North Dakota",
                    "Ohio",
                    "Oklahoma",
                    "Oregon",
                    "Pennsylvania",
                    "Puerto Rico",
                    "Rhode Island",
                    "South Carolina",
                    "South Dakota",
                    "Tennessee",
                    "Texas",
                    "Utah",
                    "Vermont",
                    "Virginia",
                    "Washington",
                    "West Virginia",
                    "Wisconsin"
                ],
                "description": "Filing State :",
                "index": 0,
                "layout": "IPY_MODEL_695f07c49bb64140886e60ea494b3738",
                "style": "IPY_MODEL_7d87072d6cca44b09d4f64b7ff8e2e30"
            }
        },
        "1686b63f1da442d89d8727577d0342d2": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "1687645a48ac475ab30cf820eb0063e6": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "16f49e6efe664716bca963eecc8a50ab": {
            "model_name": "VBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_53b828ad2e1445b3b77341fe8a8b0eba",
                    "IPY_MODEL_9abbfe66553740d88412b7209426e00a",
                    "IPY_MODEL_1c5fa0a035944c4199f6d5dd3f82c033"
                ],
                "layout": "IPY_MODEL_4cf5b9366259456d8ce51f431d6b7e0a"
            }
        },
        "170b2bf62a1e478aa80a292fc41eb4ce": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "17a812e43cef433783459ae473ce4019": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "17f23f730a2c4f56aec312f50aff71bb": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "1815b04cae2541359ca2e69a71a74b08": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "183d3ef6fc534780b14db5e052b0cf39": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "184c7044f4c440d8b040606cba4e8940": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "18f7e0c5e41847a2bc670171d2fdc0d4": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "19bf15d1a62e4634accf0802167333ff": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_d2dda1f653864763b18ed1708c14248e"
                ],
                "layout": "IPY_MODEL_01599ca60b4940b283c6e1bfc7cdc398"
            }
        },
        "19cc613d546448f9b867cfc185bddc45": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_808d96767edb451184194881d5ac3aac"
                ],
                "layout": "IPY_MODEL_4663ca64e37e4b24ad5487e40d50cbb4"
            }
        },
        "19dd831cb42948a8a6b168d9b2855bbc": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "19fc15bb00de4d73a374ce7eb2a7facc": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "1a499900eb284f1eb055535f3ef618fb": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "1a536be7a13d496db6770f2cd4f6463d": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "1aa33b925498494ab83e0c9b221c7065": {
            "model_name": "FigureModel",
            "model_module": "plotlywidget",
            "model_module_version": "0.9.1",
            "state": {
                "_config": {
                    "plotlyServerURL": "https://plot.ly"
                },
                "_data": [
                    {
                        "orientation": "v",
                        "type": "bar",
                        "uid": "a180d3f2-3448-441a-9833-52f00a9f14c5",
                        "x": [
                            "Credit Card",
                            "Debit Card",
                            "Deposit Account"
                        ],
                        "y": [
                            1045,
                            13804,
                            24168
                        ]
                    }
                ],
                "_js2py_restyle": {},
                "_js2py_update": {},
                "_last_layout_edit_id": 5,
                "_last_trace_edit_id": 4,
                "_layout": {
                    "autosize": true,
                    "barmode": "group",
                    "hovermode": "closest",
                    "template": {},
                    "title": {
                        "text": "SAR Filings by State and Product"
                    },
                    "xaxis": {
                        "title": {
                            "text": "SARs Filing Type"
                        }
                    },
                    "yaxis": {
                        "title": {
                            "text": "Number of Filings"
                        }
                    }
                },
                "_model_module_version": "0.9.1",
                "_py2js_addTraces": {},
                "_py2js_animate": {},
                "_py2js_deleteTraces": {},
                "_py2js_moveTraces": {},
                "_py2js_removeLayoutProps": {},
                "_py2js_removeTraceProps": {},
                "_py2js_restyle": {},
                "_view_count": 0,
                "_view_module_version": "0.9.1"
            }
        },
        "1ab690206aa2436faea4ad8bdd6cab2a": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "Alabama",
                    "Arizona",
                    "Arkansas",
                    "California",
                    "Colorado",
                    "Connecticut",
                    "Delaware",
                    "District of Columbia",
                    "Florida",
                    "Georgia",
                    "Hawaii",
                    "Idaho",
                    "Illinois",
                    "Indiana",
                    "Iowa",
                    "Kansas",
                    "Kentucky",
                    "Louisiana",
                    "Maine",
                    "Maryland",
                    "Massachusetts",
                    "Michigan",
                    "Minnesota",
                    "Mississippi",
                    "Missouri",
                    "Montana",
                    "Nebraska",
                    "Nevada",
                    "New Hampshire",
                    "New Jersey",
                    "New Mexico",
                    "New York",
                    "North Carolina",
                    "North Dakota",
                    "Ohio",
                    "Oklahoma",
                    "Oregon",
                    "Pennsylvania",
                    "Puerto Rico",
                    "Rhode Island",
                    "South Carolina",
                    "South Dakota",
                    "Tennessee",
                    "Texas",
                    "Utah",
                    "Vermont",
                    "Virginia",
                    "Washington",
                    "West Virginia",
                    "Wisconsin"
                ],
                "description": "Filing State :",
                "index": 0,
                "layout": "IPY_MODEL_8d9e44576f354c608f3d49a338abfa7c",
                "style": "IPY_MODEL_fedd3e0ecc004c30bd704eb225d00107"
            }
        },
        "1abf20c1ca0c4001b87b9e21d404adda": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "OCC",
                    "FDIC",
                    "SEC",
                    "FHFA",
                    "CFTC"
                ],
                "description": "Regulator :",
                "index": 0,
                "layout": "IPY_MODEL_e6c51ef6db3e4c9fa64bbaf9f391cf0e",
                "style": "IPY_MODEL_3a7eb3d892ad438395b3f58ec16cd5c1"
            }
        },
        "1af5d72bd81848d8a8e81459ebbbb60b": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "1b216dfe9f7140759f7e4e6d6cadcfbf": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "1b5d8f28429f4e1da1dfd2f9fa9490cd": {
            "model_name": "FigureModel",
            "model_module": "plotlywidget",
            "model_module_version": "0.9.1",
            "state": {
                "_config": {
                    "plotlyServerURL": "https://plot.ly"
                },
                "_data": [
                    {
                        "orientation": "v",
                        "text": {
                            "dtype": "float64",
                            "shape": [
                                1149
                            ]
                        },
                        "textposition": "auto",
                        "type": "bar",
                        "uid": "d286e708-0a26-4d6a-8452-e55eb21d38e4",
                        "x": [
                            "Debit Card",
                            "Deposit Account"
                        ],
                        "y": [
                            223,
                            493
                        ]
                    }
                ],
                "_js2py_restyle": {},
                "_js2py_update": {},
                "_last_layout_edit_id": 1,
                "_layout": {
                    "annotations": [
                        {
                            "font": {
                                "color": "red",
                                "size": 10
                            },
                            "showarrow": false,
                            "text": "Source: FINCEN.gov",
                            "x": 1,
                            "xanchor": "right",
                            "xref": "paper",
                            "xshift": 0,
                            "y": -0.15,
                            "yanchor": "auto",
                            "yref": "paper",
                            "yshift": 0
                        }
                    ],
                    "autosize": true,
                    "barmode": "group",
                    "hovermode": "closest",
                    "template": {},
                    "title": {
                        "text": "SAR Filings by State and Product"
                    }
                },
                "_model_module_version": "0.9.1",
                "_py2js_addTraces": {},
                "_py2js_animate": {},
                "_py2js_deleteTraces": {},
                "_py2js_moveTraces": {},
                "_py2js_removeLayoutProps": {},
                "_py2js_removeTraceProps": {},
                "_py2js_restyle": {},
                "_py2js_update": {},
                "_view_count": 0,
                "_view_module_version": "0.9.1"
            },
            "buffers": [
                {
                    "data": "AAAAAADAVkAAAAAAAOBrQAAAAAAAAHFAAAAAAABQcUAAAAAAAEB1QAAAAAAAYHxAAAAAAACwdEAAAAAAANB+QAAAAAAA4GdAAAAAAABgaEAAAAAAANBwQAAAAAAAkHFAAAAAAACgcUAAAAAAAHB7QAAAAAAAIIhAAAAAAABgnEAAAAAAAIiUQAAAAAAA+JtAAAAAAAD2oEAAAAAAAACqQAAAAAAAsKpAAAAAAAArsEAAAAAAABixQAAAAAAAQGdAAAAAAAAAkUAAAAAAAH6xQAAAAAAAgFhAAAAAAABgekAAAAAAAIBZQAAAAAAA4GBAAAAAAAAAYUAAAAAAAABgQAAAAAAAAG1AAAAAAABAdEAAAAAAAIB8QAAAAAAA8H5AAAAAAACghEAAAAAAAGiOQAAAAAAAAFlAAAAAAABggEAAAAAAAICBQAAAAAAAgFdAAAAAAABAWEAAAAAAAIBYQAAAAAAAQFpAAAAAAABAYEAAAAAAAMBhQAAAAAAAYGVAAAAAAADAZ0AAAAAAAOBrQAAAAAAAmqBAAAAAAADOqUAAAAAAADKqQAAAAAAAbq1AAAAAAAA4sEAAAAAAAE+xQAAAAAAAI7ZAAAAAAAAAVUAAAAAAAIBZQAAAAAAAgF1AAAAAAADAYUAAAAAAAKBiQAAAAAAAgGNAAAAAAAAAZ0AAAAAAACBnQAAAAAAAwGpAAAAAAADAcUAAAAAAAOByQAAAAAAA0HpAAAAAAACSvUAAAAAAgPHGQAAAAABAxdBAAAAAAADN00AAAAAAQOPYQAAAAABAhtpAAAAAAIBh3EAAAAAAAIBiQAAAAAAAIHNAAAAAAAAOtEAAAAAAAK3AQAAAAAAAbOFAAAAAAABAVkAAAAAAAEBeQAAAAAAAoGhAAAAAAABgYEAAAAAAAMBgQAAAAAAAAGJAAAAAAACAbEAAAAAAAMBVQAAAAAAAgFpAAAAAAACAYUAAAAAAAMBhQAAAAAAA4GRAAAAAAACAZUAAAAAAACBpQAAAAAAAgFtAAAAAAAAgZUAAAAAAACBrQAAAAAAA4GtAAAAAAAAQcEAAAAAAAGBwQAAAAAAAqIVAAAAAAABiokAAAAAAADCyQAAAAAAA7rJAAAAAAADstkAAAAAAACi4QAAAAAAAAGNAAAAAAACgZEAAAAAAAGBmQAAAAAAAMHZAAAAAAACgeUAAAAAAAMB+QAAAAAAA8H9AAAAAAABgYUAAAAAAAHBwQAAAAAAAyIJAAAAAAAB4h0AAAAAAAMCJQAAAAAAAsI1AAAAAAADokEAAAAAAAMCTQAAAAAAAoGlAAAAAAACAdkAAAAAAAOiOQAAAAAAAjJBAAAAAAAAwl0AAAAAAAOCZQAAAAAAAxJ1AAAAAAADwfkAAAAAAAECGQAAAAAAAvKRAAAAAAABAVkAAAAAAAEBdQAAAAAAAAF5AAAAAAADwc0AAAAAAAAB6QAAAAAAAwFRAAAAAAACwcUAAAAAAAAB4QAAAAAAAAF1AAAAAAABAXUAAAAAAAABeQAAAAAAA4GBAAAAAAACgYUAAAAAAAOBjQAAAAAAAIGFAAAAAAAAQeUAAAAAAAHCJQAAAAAAAMJJAAAAAAAC0lEAAAAAAACydQAAAAAAA8J1AAAAAAACAoUAAAAAAAKB6QAAAAAAAaIdAAAAAAAAUpUAAAAAAAMBcQAAAAAAAgF5AAAAAAABAWkAAAAAAAABsQAAAAAAAEHVAAAAAAADggUAAAAAAAFCDQAAAAAAAAFtAAAAAAABSpkAAAAAAACe1QAAAAAAAcbhAAAAAAACWvEAAAAAAAAG9QAAAAAAARb5AAAAAAAC4v0AAAAAAACzGQAAAAADAStZAAAAAAIDi3kAAAAAAoOPgQAAAAACAb+JAAAAAAKDA4kAAAAAAYG/kQAAAAAAAgFRAAAAAAAAAXEAAAAAAAMBdQAAAAAAAIGJAAAAAAAAgaEAAAAAAABBzQAAAAAAAYHdAAAAAAACweUAAAAAAACCBQAAAAAAAIIJAAAAAAAAghUAAAAAAAPSQQAAAAAAA0JFAAAAAAADkmEAAAAAAAIBXQAAAAAAAeJJAAAAAAAAck0AAAAAAAJ6qQAAAAAAAoGtAAAAAAABAcEAAAAAAAMBxQAAAAAAAQINAAAAAAADIhUAAAAAAAKBlQAAAAAAA8HNAAAAAAADAfkAAAAAAAMiEQAAAAAAAcIVAAAAAAAAgi0AAAAAAAMCNQAAAAAAAQF1AAAAAAACIjEAAAAAAAHB4QAAAAAAA+IBAAAAAAACwgkAAAAAAAMBZQAAAAAAAWIVAAAAAAAC4jUAAAAAAAIiPQAAAAAAAtJBAAAAAAADAkEAAAAAAAACRQAAAAAAAxJRAAAAAAAAAVUAAAAAAAABWQAAAAAAAQFdAAAAAAACAW0AAAAAAAMBgQAAAAAAA4GFAAAAAAADAZkAAAAAAAOBrQAAAAAAAIG1AAAAAAAAgckAAAAAAAJynQAAAAAAA/bNAAAAAAAD8wUAAAAAAAIPCQAAAAAAAjclAAAAAAIC2ykAAAAAAAD7NQAAAAAAAIGZAAAAAAACAZ0AAAAAAAJCSQAAAAAAAlK1AAAAAAABn0EAAAAAAAEBrQAAAAAAAQFhAAAAAAABAWkAAAAAAACBhQAAAAAAAQGFAAAAAAACgYkAAAAAAAMBxQAAAAAAAeqtAAAAAAABAV0AAAAAAAABYQAAAAAAAQFxAAAAAAAAAYEAAAAAAAABaQAAAAAAA4GNAAAAAAABAaUAAAAAAAABqQAAAAAAAEHRAAAAAAAAQdEAAAAAAAJB2QAAAAAAAAFtAAAAAAAAgYUAAAAAAAKBhQAAAAAAAwGRAAAAAAAAAZkAAAAAAACBpQAAAAAAAEHBAAAAAAABUmkAAAAAAABqmQAAAAAAA2K5AAAAAAABgtEAAAAAAAB65QAAAAAAArbtAAAAAAACavkAAAAAAAEBeQAAAAAAABJdAAAAAAABQm0AAAAAAAGi2QAAAAAAAgFdAAAAAAABQhEAAAAAAAHCEQAAAAAAAgGBAAAAAAADAZUAAAAAAAABoQAAAAAAAwGlAAAAAAADgb0AAAAAAAOBlQAAAAAAAcH5AAAAAAADIgUAAAAAAAJCFQAAAAAAA6IhAAAAAAACIikAAAAAAAACOQAAAAAAACI9AAAAAAABckkAAAAAAAIBUQAAAAAAAwFZAAAAAAABAWEAAAAAAAIBYQAAAAAAA4GBAAAAAAAA4okAAAAAAABCuQAAAAAAA0bdAAAAAAAA4vEAAAAAAgEPBQAAAAACAJMJAAAAAAAC0w0AAAAAAAKB7QAAAAAAAoJZAAAAAAAACpkAAAAAAgNTGQAAAAAAAwF9AAAAAAACAdEAAAAAAAGB4QAAAAAAAgFlAAAAAAAAAWkAAAAAAAIBaQAAAAAAAwF5AAAAAAAAAYUAAAAAAAOBiQAAAAAAAQFVAAAAAAADAVUAAAAAAAKBzQAAAAAAAWIFAAAAAAAC8k0AAAAAAANiTQAAAAAAABJRAAAAAAAA8mEAAAAAAAAybQAAAAAAAgGNAAAAAAABogUAAAAAAAMCPQAAAAAAA7qhAAAAAAACAVkAAAAAAAEBYQAAAAAAAgFlAAAAAAADAWUAAAAAAACBgQAAAAAAAIGRAAAAAAACAZEAAAAAAAKBtQAAAAAAAIHFAAAAAAABwdkAAAAAAAGB5QAAAAAAAIGhAAAAAAABQdkAAAAAAAAiJQAAAAAAAQFhAAAAAAACAWUAAAAAAACBiQAAAAAAAQGpAAAAAAAAwckAAAAAAACBhQAAAAAAA4HBAAAAAAACgckAAAAAAAJCAQAAAAAAASIJAAAAAAAAYhUAAAAAAAICNQAAAAAAAgFpAAAAAAADAW0AAAAAAADB4QAAAAAAA8IVAAAAAAADAXEAAAAAAAGBnQAAAAAAAgH5AAAAAAADQgkAAAAAAAKCEQAAAAAAAuIZAAAAAAABIi0AAAAAAAEBlQAAAAAAAYGtAAAAAAABIgEAAAAAAACSVQAAAAAAAgFRAAAAAAADAWUAAAAAAAEBWQAAAAAAAgFZAAAAAAADAV0AAAAAAAIBZQAAAAAAAQF5AAAAAAACAXkAAAAAAAIBWQAAAAAAAAF5AAAAAAACgakAAAAAAAMB+QAAAAAAA0IlAAAAAAAAYkUAAAAAAADiRQAAAAAAA2JFAAAAAAAAomUAAAAAAACBoQAAAAAAAEHZAAAAAAADEmEAAAAAAANSfQAAAAAAAwFxAAAAAAACAWkAAAAAAAOBnQAAAAAAAIGhAAAAAAACgaEAAAAAAAABvQAAAAAAACIJAAAAAAACAV0AAAAAAAEBaQAAAAAAAIGBAAAAAAACAY0AAAAAAAEBlQAAAAAAAAGhAAAAAAACAVUAAAAAAAABaQAAAAAAAQIdAAAAAAAC0l0AAAAAAAMSjQAAAAAAAKKVAAAAAAABwrUAAAAAAAJitQAAAAAAA87JAAAAAAACAV0AAAAAAAFBxQAAAAAAAqIJAAAAAAABgrUAAAAAAAIBWQAAAAAAAgFdAAAAAAABAWkAAAAAAAEBcQAAAAAAAQF1AAAAAAABAYkAAAAAAAGBsQAAAAAAAQFxAAAAAAAAgZEAAAAAAAGBkQAAAAAAAgGZAAAAAAABAZ0AAAAAAAMBpQAAAAAAA4G9AAAAAAAAQcUAAAAAAAGByQAAAAAAA0HJAAAAAAADgc0AAAAAAAMB3QAAAAAAAAIJAAAAAAADsk0AAAAAAABieQAAAAAAAnqBAAAAAAAD4q0AAAAAAAACuQAAAAAAAvLJAAAAAAACQdkAAAAAAABB9QAAAAAAAAH5AAAAAAAACo0AAAAAAAHarQAAAAAAAAFdAAAAAAAAAV0AAAAAAAMBYQAAAAAAAgFpAAAAAAAAgZEAAAAAAAABlQAAAAAAAQG9AAAAAAADwc0AAAAAAAIB1QAAAAAAAQHlAAAAAAAAAekAAAAAAAPiBQAAAAAAASIJAAAAAAAAgZUAAAAAAACBlQAAAAAAAIGZAAAAAAABAZ0AAAAAAAIBrQAAAAAAAwGxAAAAAAADgbUAAAAAAAGCJQAAAAAAARJVAAAAAAAAOoEAAAAAAAEyiQAAAAAAAwKdAAAAAAAAGqEAAAAAAAB6qQAAAAAAAQF5AAAAAAAAwdkAAAAAAANiLQAAAAAAA2LZAAAAAAADgaEAAAAAAACBuQAAAAAAAgHBAAAAAAADwe0AAAAAAADiDQAAAAAAA+IhAAAAAAADYi0AAAAAAAABaQAAAAAAAIGBAAAAAAACgZkAAAAAAAKBpQAAAAAAA4GxAAAAAAABAdUAAAAAAAGyQQAAAAAAA4GBAAAAAAADgc0AAAAAAAOB6QAAAAAAA6IRAAAAAAACAhkAAAAAAAFSRQAAAAAAAAJJAAAAAAAAAYUAAAAAAAJB2QAAAAAAAoHZAAAAAAAACokAAAAAAADBwQAAAAAAAkHBAAAAAAADAVkAAAAAAAEBbQAAAAAAAAF5AAAAAAADgZUAAAAAAAIBnQAAAAAAAoGlAAAAAAADgbUAAAAAAAIBuQAAAAAAAkHRAAAAAAADwdEAAAAAAAMBgQAAAAAAAMHxAAAAAAABIlUAAAAAAAIBYQAAAAAAAwFpAAAAAAADAWkAAAAAAAIBcQAAAAAAAoGFAAAAAAADAYUAAAAAAAIBlQAAAAAAAwGlAAAAAAADgakAAAAAAAGiIQAAAAAAAgI1AAAAAAAA0k0AAAAAAAEyVQAAAAAAAaJhAAAAAAAB8mUAAAAAAADKhQAAAAAAAgFpAAAAAAADgakAAAAAAABiEQAAAAAAA6JpAAAAAAADAVEAAAAAAAIBVQAAAAAAAwGNAAAAAAACAVkAAAAAAACBwQAAAAAAAQH1AAAAAAAAIjkAAAAAAACiZQAAAAAAAOJ1AAAAAAABGqUAAAAAAAEB0QAAAAAAAwF9AAAAAAAAgYUAAAAAAAGBiQAAAAAAAQGZAAAAAAABgaEAAAAAAAMBvQAAAAAAAQHJAAAAAAABQckAAAAAAAGBzQAAAAAAA8IJAAAAAAAAAhUAAAAAAAEBVQAAAAAAAgFVAAAAAAAAAVkAAAAAAAEBYQAAAAAAAAFpAAAAAAABAXkAAAAAAAOBhQAAAAAAAIGVAAAAAAACgaEAAAAAAAABrQAAAAAAA4GtAAAAAAACgcEAAAAAAAJB6QAAAAAAAoIJAAAAAAAAAVUAAAAAAAIBaQAAAAAAAIGpAAAAAAAAgbEAAAAAAAOByQAAAAAAAYHZAAAAAAACQdkAAAAAAACiBQAAAAAAAUHFAAAAAAADAdUAAAAAAAOB4QAAAAAAAgHpAAAAAAABwe0AAAAAAABB9QAAAAAAAgH9AAAAAAADAg0AAAAAAAICIQAAAAAAA2IlAAAAAAABAikAAAAAAAECLQAAAAAAAcJBAAAAAAACAkEAAAAAAAEiHQAAAAAAAWJRAAAAAAADgoUAAAAAAAL6iQAAAAAAAQKlAAAAAAADoqkAAAAAAAFCtQAAAAAAA4GlAAAAAAAAoikAAAAAAAJKtQAAAAAAAAGJAAAAAAAAga0AAAAAAABBxQAAAAAAA4HhAAAAAAAAwekAAAAAAAEiAQAAAAAAAAGZAAAAAAACwekAAAAAAANB4QAAAAAAAYHpAAAAAAACAekAAAAAAABB9QAAAAAAAGIBAAAAAAAAIgkAAAAAAAMiDQAAAAAAAgFVAAAAAAAAAWEAAAAAAAIBcQAAAAAAAgF1AAAAAAAAAX0AAAAAAAEBfQAAAAAAAYGFAAAAAAACgZEAAAAAAAGBoQAAAAAAA9JRAAAAAAAAgokAAAAAAABmwQAAAAAAA9LNAAAAAAADVuEAAAAAAAPG5QAAAAAAA+7pAAAAAAAAAakAAAAAAACCYQAAAAAAAPJtAAAAAAICfwUAAAAAAAIBhQAAAAAAAwGtAAAAAAABgbkAAAAAAAMBuQAAAAAAAcHhAAAAAAADAfUAAAAAAAAyXQAAAAAAAQFdAAAAAAABAXkAAAAAAAABlQAAAAAAAoGVAAAAAAADAaEAAAAAAAEBrQAAAAAAAoGxAAAAAAACAVkAAAAAAAABjQAAAAAAAoG5AAAAAAAAwcEAAAAAAAOB5QAAAAAAAsHpAAAAAAAAQhEAAAAAAAIBWQAAAAAAAAHhAAAAAAAAggkAAAAAAAFSQQAAAAAAAcJtAAAAAAADMm0AAAAAAAHycQAAAAAAA7J1AAAAAAACwokAAAAAAAMKtQAAAAAAAQFhAAAAAAAAAW0AAAAAAAMBcQAAAAAAAQF5AAAAAAACAXkAAAAAAAKBlQAAAAAAAIGZAAAAAAACAZkAAAAAAAKBmQAAAAAAABK5AAAAAAAD6u0AAAAAAAJXJQAAAAAAA9spAAAAAAEDA0UAAAAAAgFXSQAAAAAAAq9JAAAAAAABAYUAAAAAAAOB0QAAAAAAAjqJAAAAAAACKtEAAAAAAAJrXQAAAAAAAAFVAAAAAAADAVUAAAAAAAABWQAAAAAAAwFZAAAAAAADAVUAAAAAAAEBXQAAAAAAAAFpAAAAAAABAW0AAAAAAAABhQAAAAAAAYGJAAAAAAADgZEAAAAAAAIBzQAAAAAAAwHpAAAAAAAAggkAAAAAAAPiEQAAAAAAAUIVAAAAAAAD4hUAAAAAAADCJQAAAAAAAiIpAAAAAAACAbUAAAAAAADCOQAAAAAAAzJVAAAAAAADQoEAAAAAAAJanQAAAAACA6MRAAAAAAMAb0kAAAAAAAABVQAAAAAAAwGlAAAAAAACAdEAAAAAAAFB6QAAAAAAA0HxAAAAAAABAfkAAAAAAALCfQAAAAAAAjq5AAAAAAAARuEAAAAAAAD69QAAAAAAA/r9AAAAAAIC3wEAAAAAAgHPEQAAAAAAAYJJAAAAAAAC/tEAAAAAAABjaQAAAAAAAQFVAAAAAAABgZUAAAAAAAOBmQAAAAAAAAFdAAAAAAAAAY0AAAAAAAIBkQAAAAAAAwG5AAAAAAABAeUAAAAAAALCGQAAAAAAA2IpAAAAAAACAWUAAAAAAAEBjQAAAAAAAyJ1AAAAAAABgrEAAAAAAAL6sQAAAAAAACLJAAAAAAAAzuUAAAAAAAEDEQAAAAADAFtFAAAAAAACAVkAAAAAAAIBbQAAAAAAAQHVAAAAAAAAgmkAAAAAAAHSzQAAAAAAAX7RAAAAAAADKtUAAAAAAAMfAQAAAAAAAhcJAAAAAAICIxkAAAAAAAFyWQAAAAAAA9KZAAAAAAABQsUAAAAAAAJOzQAAAAAAAMbtAAAAAAAB9vUAAAAAAgFPAQAAAAAAAgFRAAAAAAAAQe0AAAAAAAATAQAAAAACAjOFAAAAAAAAAV0AAAAAAAEBeQAAAAAAAwGBAAAAAAABgbEAAAAAAAEB5QAAAAAAAQF5AAAAAAAC0mEAAAAAAAHCfQAAAAAAAUKFAAAAAAADaokAAAAAAADKlQAAAAAAAvKpAAAAAAAAXsUAAAAAAAABWQAAAAAAAAFdAAAAAAAAAaUAAAAAAAOB6QAAAAAAA+IFAAAAAAAAAikAAAAAAACiMQAAAAAAAOJJAAAAAAAB0l0AAAAAAAGB3QAAAAAAAMH5AAAAAAAAEnkAAAAAAAEBUQAAAAAAAAFxAAAAAAABAX0AAAAAAAEB8QAAAAAAAkH9AAAAAAADQgUAAAAAAABiGQAAAAAAAAFdAAAAAAAAAWUAAAAAAAEBcQAAAAAAAgGBAAAAAAAAAY0AAAAAAAABjQAAAAAAAQGNAAAAAAACAVEAAAAAAAIBXQAAAAAAAwFlAAAAAAABAXUAAAAAAAABxQAAAAAAAYHxAAAAAAADgjUAAAAAAAPiOQAAAAAAAnJVAAAAAAADglkAAAAAAAKCbQAAAAAAAQFpAAAAAAABAeUAAAAAAACCIQAAAAAAAHqBAAAAAAAAAVUAAAAAAAOBmQAAAAAAAgHJAAAAAAABwekAAAAAAACiCQAAAAAAAkINAAAAAAABwhkAAAAAAANCIQAAAAAAAAFxAAAAAAAAAX0AAAAAAAOBpQAAAAAAA4GpAAAAAAAAwcEAAAAAAACBxQAAAAAAAQHFAAAAAAADohkAAAAAAAJyXQAAAAAAAoqVAAAAAAAA4r0AAAAAAAC6xQAAAAAAAB7dAAAAAAABRukAAAAAAAEBxQAAAAAAAeIlAAAAAAAB4mkAAAAAAAHfCQAAAAAAAAGVAAAAAAAAAZUAAAAAAAJB0QAAAAAAAkHpAAAAAAACIgEAAAAAAAGiCQAAAAAAAmIZAAAAAAADAcEAAAAAAAOB6QAAAAAAAUHxAAAAAAAAQgEAAAAAAADCDQAAAAAAAkINAAAAAAAD4hkAAAAAAAABiQAAAAAAAwFdAAAAAAADAXUAAAAAAAEBhQAAAAAAAoGVAAAAAAABAVEAAAAAAAMBiQAAAAAAAgGlAAAAAAACQd0AAAAAAAESWQAAAAAAAgFpAAAAAAAAgY0AAAAAAAABmQAAAAAAAoG5AAAAAAADgcEAAAAAAADByQAAAAAAAYHJAAAAAAAAgc0AAAAAAADB3QAAAAAAAYHdAAAAAAAB4gkAAAAAAANiDQAAAAAAAzJBAAAAAAAAkkUAAAAAAAOyUQAAAAAAAAFhAAAAAAABgYEAAAAAAABB+QAAAAAAA/JFAAAAAAABAVEAAAAAAAABcQAAAAAAAAF5AAAAAAABAbEAAAAAAANByQAAAAAAAEHRAAAAAAACQeEAAAAAAAOB4QAAAAAAAWIFAAAAAAABYgUAAAAAAAEBUQAAAAAAAQFRAAAAAAAAAVkAAAAAAAIBZQAAAAAAAAF5AAAAAAADAYUAAAAAAAJB3QAAAAAAA0IVAAAAAAACoh0AAAAAAAIiUQAAAAAAAdJZAAAAAAAD0mkAAAAAAADSgQAAAAAAA4GlAAAAAAABAjkAAAAAAAESRQAAAAAAAdKBAAAAAAABsuUAAAAAAAMi9QAAAAACAOsNAAAAAAIByw0AAAAAAgMjDQAAAAACACMRAAAAAAAAjxEAAAAAAAMBgQAAAAAAA4HZAAAAAAACAgEAAAAAAABCKQAAAAAAAKIpAAAAAAAAQckAAAAAAACB7QAAAAAAAgFZAAAAAAAAgZUAAAAAAAABvQAAAAAAAgFVAAAAAAACAWkAAAAAAAMBaQAAAAAAAQFxAAAAAAAAQcEAAAAAAAIBWQAAAAAAAwFtAAAAAAAAgd0AAAAAAAOCIQAAAAAAAgIlAAAAAAACAl0AAAAAAAGCYQAAAAAAAeJ9AAAAAAACqo0AAAAAAAEB0QAAAAAAAQHZAAAAAAAAAnEAAAAAAAMSdQAAAAAAAwGhAAAAAAABQcEAAAAAAADB3QAAAAAAAwHhAAAAAAAAAW0AAAAAAAEBgQAAAAAAAgGVAAAAAAABAaEAAAAAAANiIQAAAAAAAEJJAAAAAAAAIk0AAAAAAANyTQAAAAAAAaJRAAAAAAACYlEAAAAAAACSYQAAAAAAAgFRAAAAAAABgY0AAAAAAAMBlQAAAAAAAwGZAAAAAAABgZ0AAAAAAAPByQAAAAAAAgHZAAAAAAAD8pkAAAAAAAIS1QAAAAACA5MNAAAAAAID6xUAAAAAAAGPMQAAAAACAgM9AAAAAAIAO0UAAAAAAAABgQAAAAAAAkHVAAAAAAAAyoEAAAAAAAISvQAAAAADA8tJAAAAAAAAAV0AAAAAAAIBUQAAAAAAAYGFAAAAAAADAZkAAAAAAAEBrQAAAAAAAgH5AAAAAAADAVEAAAAAAAIBVQAAAAAAAQFpAAAAAAACAW0AAAAAAAEBdQAAAAAAAQGFAAAAAAABgZUAAAAAAAABoQAAAAAAAoGhAAAAAAABgY0AAAAAAADB4QAAAAAAA8IJAAAAAAACQhkAAAAAAADSXQAAAAAAAn7BAAAAAAACAVEAAAAAAAEBVQAAAAAAAwFlAAAAAAABAWkAAAAAAADB3QAAAAAAAoHhAAAAAAADQf0AAAAAAAECDQAAAAAAAoIVAAAAAAAAQhkAAAAAAACSQQAAAAAAAMJdAAAAAAAC4nUAAAAAAAGqlQAAAAAAASKhAAAAAAADwrkAAAAAAAPaxQAAAAAAAdbRAAAAAAADAWkAAAAAAAABmQAAAAAAAAGxAAAAAAADwcUAAAAAAAOByQAAAAAAAEHNAAAAAAABgdUAAAAAAAPB1QAAAAAAAkHdAAAAAAABQeUAAAAAAAOBnQAAAAAAAYGlAAAAAAAB4mUAAAAAAAABaQAAAAAAAAF5AAAAAAADgZUAAAAAAACybQAAAAAAAXJxAAAAAAABqsEAAAAAAAABYQAAAAAAAwGFAAAAAAADet0AAAAAAADnCQAAAAADAoNFAAAAAAEBi1EAAAAAAwNPaQAAAAADgyONAAAAAAMDY7EAAAAAAAIBaQAAAAAAAwGJAAAAAAADAZEAAAAAAAOBlQAAAAAAAEIRAAAAAAADok0AAAAAAALKiQAAAAAAApKZAAAAAAAAAqUAAAAAAAPSuQAAAAAAAUbBAAAAAAAAgfEAAAAAAAECEQAAAAAAAO75AAAAAAACAWEAAAAAAAABfQAAAAAAAgFtAAAAAAADgbkAAAAAAAABjQAAAAAAAoGVAAAAAAACgZUAAAAAAAKBtQAAAAAAAgHNAAAAAAADAZUAAAAAAACBrQAAAAAAAQGtAAAAAAAAgbEAAAAAAAMBtQAAAAAAAYHBAAAAAAAAgcUAAAAAAAABdQAAAAAAAoGNAAAAAAACAZEAAAAAAAABoQAAAAAAAgHFAAAAAAACghUAAAAAAANyRQAAAAAAAqJtAAAAAAACEoEAAAAAAAEqlQAAAAAAAEqhAAAAAAAAKrEAAAAAAAABdQAAAAAAAkIlAAAAAAAAkm0AAAAAAADWwQAAAAAAAwFdAAAAAAACAWEAAAAAAAEBcQAAAAAAAQF5AAAAAAABAWEAAAAAAAIBaQAAAAAAAwFtAAAAAAACgYkAAAAAAAKBlQAAAAAAAAGBAAAAAAADgY0AAAAAAAEBkQAAAAAAAwGdAAAAAAAAgaUAAAAAAAJB1QAAAAAAAEH1AAAAAAABAVEAAAAAAAMBUQAAAAAAAwFVAAAAAAAAAWEAAAAAAAJB3QAAAAAAA0INAAAAAAAAgbUAAAAAAAABxQAAAAAAAWIBAAAAAAAC4hkAAAAAAAECIQAAAAAAAwIhAAAAAAABAjEAAAAAAAIBjQAAAAAAAIHVAAAAAAADYgUAAAAAAACqhQAAAAAAAwF9A",
                    "path": [
                        "_data",
                        0,
                        "text",
                        "value"
                    ],
                    "encoding": "base64"
                }
            ]
        },
        "1b74d5410f4c49c1b7c0c03027c2e55c": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "OCC",
                    "FDIC",
                    "SEC",
                    "FHFA",
                    "CFTC"
                ],
                "description": "Regulator :",
                "index": 0,
                "layout": "IPY_MODEL_dbdc47a786d5422996e4f0dd29a8dd98",
                "style": "IPY_MODEL_21108a2719ee42adaf7eeefce55c7e74"
            }
        },
        "1b7f47ca0fc54470a5c9357c1289f90b": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "Alabama",
                    "Arizona",
                    "Arkansas",
                    "California",
                    "Colorado",
                    "Connecticut",
                    "Delaware",
                    "District of Columbia",
                    "Florida",
                    "Georgia",
                    "Hawaii",
                    "Idaho",
                    "Illinois",
                    "Indiana",
                    "Iowa",
                    "Kansas",
                    "Kentucky",
                    "Louisiana",
                    "Maine",
                    "Maryland",
                    "Massachusetts",
                    "Michigan",
                    "Minnesota",
                    "Mississippi",
                    "Missouri",
                    "Montana",
                    "Nebraska",
                    "Nevada",
                    "New Hampshire",
                    "New Jersey",
                    "New Mexico",
                    "New York",
                    "North Carolina",
                    "North Dakota",
                    "Ohio",
                    "Oklahoma",
                    "Oregon",
                    "Pennsylvania",
                    "Puerto Rico",
                    "Rhode Island",
                    "South Carolina",
                    "South Dakota",
                    "Tennessee",
                    "Texas",
                    "Utah",
                    "Vermont",
                    "Virginia",
                    "Washington",
                    "West Virginia",
                    "Wisconsin"
                ],
                "description": "Filing State :",
                "index": 0,
                "layout": "IPY_MODEL_f3064b0115c34f7186d69a6da85af024",
                "style": "IPY_MODEL_90082147a74a4c408726267357442111"
            }
        },
        "1c366e49e0154850a6b8dfd4eab0ced5": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "Alabama",
                    "Arizona",
                    "Arkansas",
                    "California",
                    "Colorado",
                    "Connecticut",
                    "Delaware",
                    "District of Columbia",
                    "Florida",
                    "Georgia",
                    "Hawaii",
                    "Idaho",
                    "Illinois",
                    "Indiana",
                    "Iowa",
                    "Kansas",
                    "Kentucky",
                    "Louisiana",
                    "Maine",
                    "Maryland",
                    "Massachusetts",
                    "Michigan",
                    "Minnesota",
                    "Mississippi",
                    "Missouri",
                    "Montana",
                    "Nebraska",
                    "Nevada",
                    "New Hampshire",
                    "New Jersey",
                    "New Mexico",
                    "New York",
                    "North Carolina",
                    "North Dakota",
                    "Ohio",
                    "Oklahoma",
                    "Oregon",
                    "Pennsylvania",
                    "Puerto Rico",
                    "Rhode Island",
                    "South Carolina",
                    "South Dakota",
                    "Tennessee",
                    "Texas",
                    "Utah",
                    "Vermont",
                    "Virginia",
                    "Washington",
                    "West Virginia",
                    "Wisconsin"
                ],
                "description": "Filing State :",
                "index": 0,
                "layout": "IPY_MODEL_459ad405e8cd4178b75c1efb58124ce2",
                "style": "IPY_MODEL_7850f6e5058d40309d093ad8844071e4"
            }
        },
        "1c5fa0a035944c4199f6d5dd3f82c033": {
            "model_name": "FigureModel",
            "model_module": "plotlywidget",
            "model_module_version": "0.9.1",
            "state": {
                "_config": {
                    "plotlyServerURL": "https://plot.ly"
                },
                "_data": [
                    {
                        "orientation": "v",
                        "type": "bar",
                        "uid": "24d1bad3-e2ab-4776-ac24-b0b46c6470f6",
                        "x": [
                            "Debit Card",
                            "Deposit Account"
                        ],
                        "y": [
                            223,
                            493
                        ]
                    }
                ],
                "_js2py_restyle": {},
                "_js2py_update": {},
                "_last_layout_edit_id": 1,
                "_layout": {
                    "annotations": [
                        {
                            "font": {
                                "color": "red",
                                "size": 10
                            },
                            "showarrow": false,
                            "text": "Source: FINCEN.gov",
                            "x": 1,
                            "xanchor": "right",
                            "xref": "paper",
                            "xshift": 0,
                            "y": -0.15,
                            "yanchor": "auto",
                            "yref": "paper",
                            "yshift": 0
                        }
                    ],
                    "autosize": true,
                    "barmode": "group",
                    "hovermode": "closest",
                    "template": {},
                    "title": {
                        "text": "SAR Filings by State and Product"
                    }
                },
                "_model_module_version": "0.9.1",
                "_py2js_addTraces": {},
                "_py2js_animate": {},
                "_py2js_deleteTraces": {},
                "_py2js_moveTraces": {},
                "_py2js_removeLayoutProps": {},
                "_py2js_removeTraceProps": {},
                "_py2js_restyle": {},
                "_py2js_update": {},
                "_view_count": 0,
                "_view_module_version": "0.9.1"
            }
        },
        "1d05ece61e2f46579bb467bdbf172f10": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "1d128f6f386d4f89b61d1a2890b4ae33": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "1d28792b3ff448438a7f27aa74236b8e": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_3c51345f35114f35a54fc4f4d3ba0fbb"
                ],
                "layout": "IPY_MODEL_e8917b02ba8a4713917ba24889a55e9c"
            }
        },
        "1dbff8766f63488789de68ff8e89e677": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "1dc160b1b42a41ffbf6f83c018ad52cc": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_5f2c3e5ab0954b0096cfa08814839ef4"
                ],
                "layout": "IPY_MODEL_c3e696ae262f4ee094564a5d41e2209a"
            }
        },
        "1dc4de0098ed4a568aafe628bd2d2928": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_459e3a280cb649f0b3128bd2211cab64"
                ],
                "layout": "IPY_MODEL_7eae4bb2da95430b8e4d0ac37ce70bf3"
            }
        },
        "1deb3f2ce9c04b96804ea5ef14bbc7f1": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "1ea48e77a21c4c52ad94643779487907": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "1eb6a95e13b447228c719c650ddecf57": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "1ef03151fee3473ba9fb0dccd0465aed": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "1f27a990601a46708447cf3d408336c6": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "Alabama",
                    "Arizona",
                    "Arkansas",
                    "California",
                    "Colorado",
                    "Connecticut",
                    "Delaware",
                    "District of Columbia",
                    "Florida",
                    "Georgia",
                    "Hawaii",
                    "Idaho",
                    "Illinois",
                    "Indiana",
                    "Iowa",
                    "Kansas",
                    "Kentucky",
                    "Louisiana",
                    "Maine",
                    "Maryland",
                    "Massachusetts",
                    "Michigan",
                    "Minnesota",
                    "Mississippi",
                    "Missouri",
                    "Montana",
                    "Nebraska",
                    "Nevada",
                    "New Hampshire",
                    "New Jersey",
                    "New Mexico",
                    "New York",
                    "North Carolina",
                    "North Dakota",
                    "Ohio",
                    "Oklahoma",
                    "Oregon",
                    "Pennsylvania",
                    "Puerto Rico",
                    "Rhode Island",
                    "South Carolina",
                    "South Dakota",
                    "Tennessee",
                    "Texas",
                    "Utah",
                    "Vermont",
                    "Virginia",
                    "Washington",
                    "West Virginia",
                    "Wisconsin"
                ],
                "description": "Filing State :",
                "index": 0,
                "layout": "IPY_MODEL_d4eef7a128a14888a6f2ac72c94820ce",
                "style": "IPY_MODEL_111339e3a67f4100b49f153f5a912f88"
            }
        },
        "1f3a907f5ccc4804b4c1f217ef8ea77f": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "Alabama",
                    "Arizona",
                    "Arkansas",
                    "California",
                    "Colorado",
                    "Connecticut",
                    "Delaware",
                    "District of Columbia",
                    "Florida",
                    "Georgia",
                    "Hawaii",
                    "Idaho",
                    "Illinois",
                    "Indiana",
                    "Iowa",
                    "Kansas",
                    "Kentucky",
                    "Louisiana",
                    "Maine",
                    "Maryland",
                    "Massachusetts",
                    "Michigan",
                    "Minnesota",
                    "Mississippi",
                    "Missouri",
                    "Montana",
                    "Nebraska",
                    "Nevada",
                    "New Hampshire",
                    "New Jersey",
                    "New Mexico",
                    "New York",
                    "North Carolina",
                    "North Dakota",
                    "Ohio",
                    "Oklahoma",
                    "Oregon",
                    "Pennsylvania",
                    "Puerto Rico",
                    "Rhode Island",
                    "South Carolina",
                    "South Dakota",
                    "Tennessee",
                    "Texas",
                    "Utah",
                    "Vermont",
                    "Virginia",
                    "Washington",
                    "West Virginia",
                    "Wisconsin"
                ],
                "description": "Filing State :",
                "index": 31,
                "layout": "IPY_MODEL_c1dd529f30714b718d5147456470a4f5",
                "style": "IPY_MODEL_e74e63809fc74181aa217a56483cd8e0"
            }
        },
        "1f3e4a24f81842f2935d483df7166cb6": {
            "model_name": "FigureModel",
            "model_module": "plotlywidget",
            "model_module_version": "0.9.1",
            "state": {
                "_config": {
                    "plotlyServerURL": "https://plot.ly"
                },
                "_data": [
                    {
                        "orientation": "v",
                        "type": "bar",
                        "uid": "cf9f5a85-8098-4960-95e3-60954feee058",
                        "x": [
                            "Credit Card",
                            "Debit Card",
                            "Deposit Account",
                            "Residential Mortgage"
                        ],
                        "y": [
                            1045,
                            13804,
                            24168,
                            72
                        ]
                    }
                ],
                "_js2py_restyle": {},
                "_js2py_update": {},
                "_last_layout_edit_id": 2,
                "_last_trace_edit_id": 1,
                "_layout": {
                    "autosize": true,
                    "barmode": "group",
                    "hovermode": "closest",
                    "template": {},
                    "title": {
                        "text": "SAR Filings by State and Product"
                    },
                    "xaxis": {
                        "title": {
                            "text": "SARs Filing Type"
                        }
                    },
                    "yaxis": {
                        "title": {
                            "text": "Number of Filings"
                        }
                    }
                },
                "_model_module_version": "0.9.1",
                "_py2js_addTraces": {},
                "_py2js_animate": {},
                "_py2js_deleteTraces": {},
                "_py2js_moveTraces": {},
                "_py2js_removeLayoutProps": {},
                "_py2js_removeTraceProps": {},
                "_py2js_restyle": {},
                "_view_count": 0,
                "_view_module_version": "0.9.1"
            }
        },
        "1f8136e5c9bb4d228d6245a8d4168466": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "1fb57be55a194618a2afa991cbfb577d": {
            "model_name": "VBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_393ba43dcb85416e8017feaa68d5efda",
                    "IPY_MODEL_70362de47508439e98f2ab01cea6702d",
                    "IPY_MODEL_b01c47f5a65d406081fd11b2a67f98c3"
                ],
                "layout": "IPY_MODEL_c0b255ba4b344325a96559462df9a731"
            }
        },
        "20091e7157e24c62876112d00cc2400d": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "200f32e5ba1c4ff7a2ec1570933d3ba2": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_85bfabb7d32441929787a9069129a381"
                ],
                "layout": "IPY_MODEL_a8b78f7ebae94220b66f077f9a089113"
            }
        },
        "20222ae82c94433894caf10c800bf6a3": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "2052b1e2a730461a977ffdb288624d37": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "OCC",
                    "FDIC",
                    "SEC",
                    "FHFA",
                    "CFTC"
                ],
                "description": "Regulator :",
                "index": 0,
                "layout": "IPY_MODEL_13c692d834694c948c099a87657534c3",
                "style": "IPY_MODEL_8e8271b384324cd39994249a1b1dfb43"
            }
        },
        "20792e57a32c4f2c9433c47a6d7904d6": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_06129b1c6243459d9e6a9fa5bdc020e1"
                ],
                "layout": "IPY_MODEL_4a33da1c38e3436588d0ae70411fe35b"
            }
        },
        "2091be7a5b914414b6187120fecf8566": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "20a15a5684aa4f9a81806537b058f84e": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "2014",
                    "2019",
                    "2015",
                    "2018",
                    "2017",
                    "2016",
                    "2012",
                    "2013"
                ],
                "description": "Date : ",
                "index": 1,
                "layout": "IPY_MODEL_09baa9befb82457a9372eae87b863bdd",
                "style": "IPY_MODEL_37f5e8d6c3f74f9ab260173a29140c73"
            }
        },
        "20c45df988b04744a2caa5962d593533": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "20c4916bc510460bb1be1d454f210997": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "20c4ced9051548ff9bf1ce6a30a28ffa": {
            "model_name": "VBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_5810240fbab7452ba672e125d0db04e4",
                    "IPY_MODEL_70158a6e99b440beaf0e5b808d120ff3",
                    "IPY_MODEL_03a401d7df404bfaaafdd48a88370492"
                ],
                "layout": "IPY_MODEL_dcdfc9b6d9b84784b10407319bfa52de"
            }
        },
        "21108a2719ee42adaf7eeefce55c7e74": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "21163b0d6db944509808dfb1ea135499": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "213c2fa85b2b4c2da48a80a63d861a94": {
            "model_name": "VBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_ac7f0b361a70435e97c59f0e496048a3",
                    "IPY_MODEL_258779e8013f4537aaaec9ae5d9c61f7",
                    "IPY_MODEL_1aa33b925498494ab83e0c9b221c7065"
                ],
                "layout": "IPY_MODEL_52cfbae5916b46549f5a57d1d86fdb25"
            }
        },
        "215baec4243b4dbbb3a4c4ba2bc11abd": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "21d09342c00946a38f491837769c851e": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "21d1d087eec64dd7bdb6e44d0fcbf627": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "Alabama",
                    "Arizona",
                    "Arkansas",
                    "California",
                    "Colorado",
                    "Connecticut",
                    "Delaware",
                    "District of Columbia",
                    "Florida",
                    "Georgia",
                    "Hawaii",
                    "Idaho",
                    "Illinois",
                    "Indiana",
                    "Iowa",
                    "Kansas",
                    "Kentucky",
                    "Louisiana",
                    "Maine",
                    "Maryland",
                    "Massachusetts",
                    "Michigan",
                    "Minnesota",
                    "Mississippi",
                    "Missouri",
                    "Montana",
                    "Nebraska",
                    "Nevada",
                    "New Hampshire",
                    "New Jersey",
                    "New Mexico",
                    "New York",
                    "North Carolina",
                    "North Dakota",
                    "Ohio",
                    "Oklahoma",
                    "Oregon",
                    "Pennsylvania",
                    "Puerto Rico",
                    "Rhode Island",
                    "South Carolina",
                    "South Dakota",
                    "Tennessee",
                    "Texas",
                    "Utah",
                    "Vermont",
                    "Virginia",
                    "Washington",
                    "West Virginia",
                    "Wisconsin"
                ],
                "description": "Filing State :",
                "index": 0,
                "layout": "IPY_MODEL_2d4f211f0fe342219823e1e3ad931efd",
                "style": "IPY_MODEL_6d08548253e54652962318fd87e0bfe1"
            }
        },
        "21e8a332e1c547ac8fd317f9b2bdd9b2": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "228da4b5d3594c9ea676bb75fb720a62": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "OCC",
                    "FDIC",
                    "SEC",
                    "FHFA",
                    "CFTC"
                ],
                "description": "Regulator :",
                "index": 0,
                "layout": "IPY_MODEL_0c3c5ab3574a4a76b8678973cfeec8f8",
                "style": "IPY_MODEL_fb4115655a054371becfec6a82bbf207"
            }
        },
        "230dad5038fb4f909010543fc612f708": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_e9b53a816aad49e49fb6ad0990791653"
                ],
                "layout": "IPY_MODEL_d40e39dd60364db2801aa76445de4efe"
            }
        },
        "23cf7bcc22924127b35d277ace132e67": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "23d850d566bc46df927584f6f89da2cc": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "OCC",
                    "FDIC",
                    "SEC",
                    "FHFA",
                    "CFTC"
                ],
                "description": "Regulator :",
                "index": 0,
                "layout": "IPY_MODEL_cc3a2750da8a4401ab2293a85d667c4e",
                "style": "IPY_MODEL_297e3531c85b467a84ce74ac47a917d6"
            }
        },
        "24f5a1cdca2e4afe815a5906d860c6af": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "OCC",
                    "FDIC",
                    "SEC",
                    "FHFA",
                    "CFTC"
                ],
                "description": "Regulator :",
                "index": 0,
                "layout": "IPY_MODEL_83222ac9d7014591ac9b96364e0ef10d",
                "style": "IPY_MODEL_91af142ad4184bbe9aeb65589f109b84"
            }
        },
        "258779e8013f4537aaaec9ae5d9c61f7": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_987c449cb29b4f0d9b037832ab394a15",
                    "IPY_MODEL_b4563c486cd6465cb8fd61352fdfa1a4"
                ],
                "layout": "IPY_MODEL_b00a39b35b6c4adf8872face38883668"
            }
        },
        "25c3ae167e7e4f939a0baffc7147a154": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_1f27a990601a46708447cf3d408336c6",
                    "IPY_MODEL_bf03736aa23f4ec5bd9261ef0975339b"
                ],
                "layout": "IPY_MODEL_645f7636b383427bb244b6d978215a8e"
            }
        },
        "25dc7e1178e94c738e8e62e677b7cf29": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_9be9b7518468469f89d5e56f7d3668b6"
                ],
                "layout": "IPY_MODEL_e3de7bbc969c4561955f6f87e2bc52ad"
            }
        },
        "26046907afe24777ba989a8a18fc2ff1": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "261ee2fcc9584d4bae4367717057fadd": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "Alabama",
                    "Arizona",
                    "Arkansas",
                    "California",
                    "Colorado",
                    "Connecticut",
                    "Delaware",
                    "District of Columbia",
                    "Florida",
                    "Georgia",
                    "Hawaii",
                    "Idaho",
                    "Illinois",
                    "Indiana",
                    "Iowa",
                    "Kansas",
                    "Kentucky",
                    "Louisiana",
                    "Maine",
                    "Maryland",
                    "Massachusetts",
                    "Michigan",
                    "Minnesota",
                    "Mississippi",
                    "Missouri",
                    "Montana",
                    "Nebraska",
                    "Nevada",
                    "New Hampshire",
                    "New Jersey",
                    "New Mexico",
                    "New York",
                    "North Carolina",
                    "North Dakota",
                    "Ohio",
                    "Oklahoma",
                    "Oregon",
                    "Pennsylvania",
                    "Puerto Rico",
                    "Rhode Island",
                    "South Carolina",
                    "South Dakota",
                    "Tennessee",
                    "Texas",
                    "Utah",
                    "Vermont",
                    "Virginia",
                    "Washington",
                    "West Virginia",
                    "Wisconsin"
                ],
                "description": "Filing State :",
                "index": 0,
                "layout": "IPY_MODEL_8b063f2856284c7a8128d0ae87f7b71a",
                "style": "IPY_MODEL_f8e3c4ad09f2462aad166f3cadc97a6b"
            }
        },
        "2626a7dd710e44baa6d131b69607cdd5": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "Alabama",
                    "Arizona",
                    "Arkansas",
                    "California",
                    "Colorado",
                    "Connecticut",
                    "Delaware",
                    "District of Columbia",
                    "Florida",
                    "Georgia",
                    "Hawaii",
                    "Idaho",
                    "Illinois",
                    "Indiana",
                    "Iowa",
                    "Kansas",
                    "Kentucky",
                    "Louisiana",
                    "Maine",
                    "Maryland",
                    "Massachusetts",
                    "Michigan",
                    "Minnesota",
                    "Mississippi",
                    "Missouri",
                    "Montana",
                    "Nebraska",
                    "Nevada",
                    "New Hampshire",
                    "New Jersey",
                    "New Mexico",
                    "New York",
                    "North Carolina",
                    "North Dakota",
                    "Ohio",
                    "Oklahoma",
                    "Oregon",
                    "Pennsylvania",
                    "Puerto Rico",
                    "Rhode Island",
                    "South Carolina",
                    "South Dakota",
                    "Tennessee",
                    "Texas",
                    "Utah",
                    "Vermont",
                    "Virginia",
                    "Washington",
                    "West Virginia",
                    "Wisconsin"
                ],
                "description": "Filing State :",
                "index": 0,
                "layout": "IPY_MODEL_df3d8c4e03a7491391dea9d8c0f1dc4e",
                "style": "IPY_MODEL_67bfefedd2614b2ca931a08e28007cc8"
            }
        },
        "2675197151674e25a187bcd83135acc8": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "267f3e4ed9934e3aaa2b06c91b7c9ff1": {
            "model_name": "VBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_aa0b55def2ca4faa9304868585e43701",
                    "IPY_MODEL_50e66f1a9d2a4674b976c7f360a12414",
                    "IPY_MODEL_d3d516aa4a554306a7c6dee14c8a50eb"
                ],
                "layout": "IPY_MODEL_e341943c42474887bfc713c70c0a8987"
            }
        },
        "26ada6e0417644fb8702d8568a13e995": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "26cc4400ce924df5ab06c3e74487cc3d": {
            "model_name": "FigureModel",
            "model_module": "plotlywidget",
            "model_module_version": "0.9.1",
            "state": {
                "_config": {
                    "plotlyServerURL": "https://plot.ly"
                },
                "_data": [
                    {
                        "orientation": "v",
                        "type": "bar",
                        "uid": "60265eb7-a634-4bb6-b544-b7ee8fd0b62a",
                        "x": [
                            "Debit Card",
                            "Deposit Account"
                        ],
                        "y": [
                            223,
                            493
                        ]
                    }
                ],
                "_js2py_restyle": {},
                "_js2py_update": {},
                "_last_layout_edit_id": 1,
                "_layout": {
                    "autosize": true,
                    "barmode": "group",
                    "hovermode": "closest",
                    "template": {},
                    "title": {
                        "text": "SAR Filings by State and Product"
                    }
                },
                "_model_module_version": "0.9.1",
                "_py2js_addTraces": {},
                "_py2js_animate": {},
                "_py2js_deleteTraces": {},
                "_py2js_moveTraces": {},
                "_py2js_removeLayoutProps": {},
                "_py2js_removeTraceProps": {},
                "_py2js_restyle": {},
                "_py2js_update": {},
                "_view_count": 0,
                "_view_module_version": "0.9.1"
            }
        },
        "27008953cb0243aba94f8cb36534495f": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "2705a0705ef94cf9b1ce0fb397b96f7b": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "2748664ec0ba49e7ad566617a3688007": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_75770fd10d8b4d0ba78d530eb667893b",
                    "IPY_MODEL_8ddee12b2ce54276a0a31e1ab43404f6"
                ],
                "layout": "IPY_MODEL_6784d99804724d2b953e5eebcf85f050"
            }
        },
        "2749ed22ac004b48b290fc8c0cd9a546": {
            "model_name": "VBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_775df3deb25b4887b36fff003678b6b8",
                    "IPY_MODEL_9b59176e0ecd474da91a28330dd5c8fc",
                    "IPY_MODEL_bcdaeeca947b4e79910bd1dcc01afcd1"
                ],
                "layout": "IPY_MODEL_2675197151674e25a187bcd83135acc8"
            }
        },
        "27638292e9964acb906ff2c5cae97bd7": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "2786307617da448dba46a00e82088a6e": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "27aff79243bd4c80978ca400d4a689b0": {
            "model_name": "FigureModel",
            "model_module": "plotlywidget",
            "model_module_version": "0.9.1",
            "state": {
                "_config": {
                    "plotlyServerURL": "https://plot.ly"
                },
                "_data": [
                    {
                        "marker": {
                            "color": "rgb(26, 118, 255)",
                            "line": {
                                "color": "rgba(100, 10, 205, 1.0)",
                                "width": 2
                            }
                        },
                        "orientation": "v",
                        "type": "bar",
                        "uid": "1aea621b-4633-4ce6-b6c9-b69ff1539c61",
                        "x": [
                            "Debit Card",
                            "Deposit Account"
                        ],
                        "y": [
                            223,
                            493
                        ]
                    }
                ],
                "_js2py_pointsCallback": {},
                "_js2py_restyle": {},
                "_js2py_update": {},
                "_last_layout_edit_id": 1,
                "_layout": {
                    "annotations": [
                        {
                            "font": {
                                "color": "red",
                                "size": 10
                            },
                            "showarrow": false,
                            "text": "Source: FINCEN.gov",
                            "x": 1,
                            "xanchor": "right",
                            "xref": "paper",
                            "xshift": 0,
                            "y": -0.15,
                            "yanchor": "auto",
                            "yref": "paper",
                            "yshift": 0
                        }
                    ],
                    "autosize": true,
                    "barmode": "group",
                    "hovermode": "closest",
                    "plot_bgcolor": "lightgreen",
                    "template": {},
                    "title": {
                        "text": "SAR Filings by State and Product"
                    }
                },
                "_model_module_version": "0.9.1",
                "_py2js_addTraces": {},
                "_py2js_animate": {},
                "_py2js_deleteTraces": {},
                "_py2js_moveTraces": {},
                "_py2js_removeLayoutProps": {},
                "_py2js_removeTraceProps": {},
                "_py2js_restyle": {},
                "_py2js_update": {},
                "_view_count": 0,
                "_view_module_version": "0.9.1"
            }
        },
        "27ea5156a4014e11a7726c6b7c3431f8": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_1417e2e28491443b9b8fe96b35ac6412"
                ],
                "layout": "IPY_MODEL_106c99bd961e448991d8d896072d0b86"
            }
        },
        "29031f2aedd14b17af0e7f47e6404691": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "OCC",
                    "FDIC",
                    "SEC",
                    "FHFA",
                    "CFTC"
                ],
                "description": "Regulator :",
                "index": 0,
                "layout": "IPY_MODEL_1234f759d0314d64b6730512ea26cbc6",
                "style": "IPY_MODEL_b6a68e5f5e574a85b9e4d9642f60b709"
            }
        },
        "2906e066e889496582a65164673f1b86": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "290d44860a1a4c2e8b6f3ec9505f9c65": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "297e3531c85b467a84ce74ac47a917d6": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "298772d169b04ed18ce29acf8389e934": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "29f1410aa1ac475a8b3ba06595acbfbe": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "2a022fb2f6d24d45bc89c19d3362ed93": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "2a079df031a842e08dce6c09b7f568ed": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "Alabama",
                    "Arizona",
                    "Arkansas",
                    "California",
                    "Colorado",
                    "Connecticut",
                    "Delaware",
                    "District of Columbia",
                    "Florida",
                    "Georgia",
                    "Hawaii",
                    "Idaho",
                    "Illinois",
                    "Indiana",
                    "Iowa",
                    "Kansas",
                    "Kentucky",
                    "Louisiana",
                    "Maine",
                    "Maryland",
                    "Massachusetts",
                    "Michigan",
                    "Minnesota",
                    "Mississippi",
                    "Missouri",
                    "Montana",
                    "Nebraska",
                    "Nevada",
                    "New Hampshire",
                    "New Jersey",
                    "New Mexico",
                    "New York",
                    "North Carolina",
                    "North Dakota",
                    "Ohio",
                    "Oklahoma",
                    "Oregon",
                    "Pennsylvania",
                    "Puerto Rico",
                    "Rhode Island",
                    "South Carolina",
                    "South Dakota",
                    "Tennessee",
                    "Texas",
                    "Utah",
                    "Vermont",
                    "Virginia",
                    "Washington",
                    "West Virginia",
                    "Wisconsin"
                ],
                "description": "Filing State :",
                "index": 0,
                "layout": "IPY_MODEL_ba4c0d252e834f22befaab7249f65ef6",
                "style": "IPY_MODEL_dc1bfe45e034486596b6533a5a6e89f4"
            }
        },
        "2a5655f2bbea4fb3a5f15cbe8cd15587": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "2014",
                    "2019",
                    "2015",
                    "2018",
                    "2017",
                    "2016",
                    "2012",
                    "2013"
                ],
                "description": "Date : ",
                "index": 1,
                "layout": "IPY_MODEL_a7bc2cca9c4e404990ed3b3a4f8fd4e2",
                "style": "IPY_MODEL_62da565d88414f1d941160c438429bfa"
            }
        },
        "2abf161ae0b74184881f7c60918d5344": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_8d737c8af1df437c80e84bc4a4358a8a"
                ],
                "layout": "IPY_MODEL_cac446f1959744d4b8e93a62ab5664a9"
            }
        },
        "2ace85f85b8646d0950a4fc5e0ee6f1c": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "2014",
                    "2019",
                    "2015",
                    "2018",
                    "2017",
                    "2016",
                    "2012",
                    "2013"
                ],
                "description": "Date : ",
                "index": 1,
                "layout": "IPY_MODEL_12c576eaf6854f02a43b8aba021151d5",
                "style": "IPY_MODEL_879d8ebc9a1a4008972a8fa30458228f"
            }
        },
        "2ae6b740c08648d8a6e94b0dc64877fd": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "2af4f214313d464590ce3bc224345b5e": {
            "model_name": "VBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_acd1a0a7dc514f7290c62090a86b4b59",
                    "IPY_MODEL_25c3ae167e7e4f939a0baffc7147a154",
                    "IPY_MODEL_977a63e6e7a247efb652ae796b44fba8"
                ],
                "layout": "IPY_MODEL_6ffc37314b2841d2b2d27c9712813143"
            }
        },
        "2b0a3519844f4654b5506eab9de40513": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "2b245b11cf4846bcaa2992c858ca3c95": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "2b6e8d10a8e54bc9b23d698da13bf7ec": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "Alabama",
                    "Arizona",
                    "Arkansas",
                    "California",
                    "Colorado",
                    "Connecticut",
                    "Delaware",
                    "District of Columbia",
                    "Florida",
                    "Georgia",
                    "Hawaii",
                    "Idaho",
                    "Illinois",
                    "Indiana",
                    "Iowa",
                    "Kansas",
                    "Kentucky",
                    "Louisiana",
                    "Maine",
                    "Maryland",
                    "Massachusetts",
                    "Michigan",
                    "Minnesota",
                    "Mississippi",
                    "Missouri",
                    "Montana",
                    "Nebraska",
                    "Nevada",
                    "New Hampshire",
                    "New Jersey",
                    "New Mexico",
                    "New York",
                    "North Carolina",
                    "North Dakota",
                    "Ohio",
                    "Oklahoma",
                    "Oregon",
                    "Pennsylvania",
                    "Puerto Rico",
                    "Rhode Island",
                    "South Carolina",
                    "South Dakota",
                    "Tennessee",
                    "Texas",
                    "Utah",
                    "Vermont",
                    "Virginia",
                    "Washington",
                    "West Virginia",
                    "Wisconsin"
                ],
                "description": "Filing State :",
                "index": 0,
                "layout": "IPY_MODEL_feceb0e43b054d01a2bf68e8924bfb74",
                "style": "IPY_MODEL_b862d214bae644b59a7821ea260a5255"
            }
        },
        "2b80da6f58a14f40aa9f888d2077bc76": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "2bdaf86213754f1f98221f3bc93725a4": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "2c612d3dbcae44408fed451c23c77474": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_2a5655f2bbea4fb3a5f15cbe8cd15587"
                ],
                "layout": "IPY_MODEL_e60bc613f6554c96b6435f058d7f62a7"
            }
        },
        "2c69f3c87bab40ed856dd3d86afad64f": {
            "model_name": "VBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_3aeb9c254c554c7aba6c230493cefdb4",
                    "IPY_MODEL_743dfc534dbc49e7940e5bb1409325fc",
                    "IPY_MODEL_7d91ec870f5d4d55b021fb95d9570c97"
                ],
                "layout": "IPY_MODEL_40f19cdf17f644c59653a9b9e1c3fb8c"
            }
        },
        "2c73fef35b114ad28e5d5bf867e4113e": {
            "model_name": "VBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_6b5f765d111c45c596f86defb17a687c",
                    "IPY_MODEL_9d6d5ece1afa454a89fdbe763f7c3b68",
                    "IPY_MODEL_a9e4828947ee4becaaa9a2b2226dcbc3"
                ],
                "layout": "IPY_MODEL_9543e56e5bf940d49bdfd40245990b0d"
            }
        },
        "2c935620ebaf4cb08953cc54ca7f4298": {
            "model_name": "FigureModel",
            "model_module": "plotlywidget",
            "model_module_version": "0.9.1",
            "state": {
                "_config": {
                    "plotlyServerURL": "https://plot.ly"
                },
                "_data": [
                    {
                        "marker": {
                            "color": "rgb(26, 118, 255)",
                            "line": {
                                "color": "rgba(100, 10, 205, 1.0)",
                                "width": 2
                            }
                        },
                        "orientation": "v",
                        "type": "bar",
                        "uid": "b5f05d5b-36d8-4529-b5db-255a24f14b02",
                        "x": [
                            "Debit Card",
                            "Deposit Account"
                        ],
                        "y": [
                            223,
                            493
                        ]
                    }
                ],
                "_js2py_layoutDelta": {
                    "layout_delta": {
                        "annotations": [
                            {
                                "align": "center",
                                "bgcolor": "rgba(0,0,0,0)",
                                "bordercolor": "rgba(0,0,0,0)",
                                "borderpad": 1,
                                "borderwidth": 1,
                                "captureevents": false,
                                "clicktoshow": false,
                                "font": {
                                    "family": "\"Open Sans\", verdana, arial, sans-serif"
                                },
                                "opacity": 1,
                                "textangle": 0,
                                "visible": true
                            }
                        ],
                        "bargap": 0.2,
                        "bargroupgap": 0,
                        "barnorm": "",
                        "calendar": "gregorian",
                        "clickmode": "event",
                        "colorscale": {
                            "diverging": [
                                [
                                    0,
                                    "rgb(5,10,172)"
                                ],
                                [
                                    0.35,
                                    "rgb(106,137,247)"
                                ],
                                [
                                    0.5,
                                    "rgb(190,190,190)"
                                ],
                                [
                                    0.6,
                                    "rgb(220,170,132)"
                                ],
                                [
                                    0.7,
                                    "rgb(230,145,90)"
                                ],
                                [
                                    1,
                                    "rgb(178,10,28)"
                                ]
                            ],
                            "sequential": [
                                [
                                    0,
                                    "rgb(220,220,220)"
                                ],
                                [
                                    0.2,
                                    "rgb(245,195,157)"
                                ],
                                [
                                    0.4,
                                    "rgb(245,160,105)"
                                ],
                                [
                                    1,
                                    "rgb(178,10,28)"
                                ]
                            ],
                            "sequentialminus": [
                                [
                                    0,
                                    "rgb(5,10,172)"
                                ],
                                [
                                    0.35,
                                    "rgb(40,60,190)"
                                ],
                                [
                                    0.5,
                                    "rgb(70,100,245)"
                                ],
                                [
                                    0.6,
                                    "rgb(90,120,245)"
                                ],
                                [
                                    0.7,
                                    "rgb(106,137,247)"
                                ],
                                [
                                    1,
                                    "rgb(220,220,220)"
                                ]
                            ]
                        },
                        "colorway": [
                            "#1f77b4",
                            "#ff7f0e",
                            "#2ca02c",
                            "#d62728",
                            "#9467bd",
                            "#8c564b",
                            "#e377c2",
                            "#7f7f7f",
                            "#bcbd22",
                            "#17becf"
                        ],
                        "dragmode": "zoom",
                        "font": {
                            "color": "#444",
                            "family": "\"Open Sans\", verdana, arial, sans-serif",
                            "size": 12
                        },
                        "height": 490,
                        "hidesources": false,
                        "hoverdistance": 20,
                        "hoverlabel": {
                            "align": "auto",
                            "font": {
                                "family": "Arial, sans-serif",
                                "size": 13
                            },
                            "namelength": 15
                        },
                        "images": [],
                        "margin": {
                            "autoexpand": true,
                            "b": 80,
                            "l": 80,
                            "pad": 0,
                            "r": 80,
                            "t": 100
                        },
                        "modebar": {
                            "activecolor": "rgba(68, 68, 68, 0.7)",
                            "bgcolor": "rgba(245, 245, 245, 0.5)",
                            "color": "rgba(68, 68, 68, 0.3)",
                            "orientation": "h"
                        },
                        "separators": ".,",
                        "shapes": [
                            {
                                "fillcolor": "rgba(0,0,0,0)",
                                "layer": "above",
                                "line": {
                                    "dash": "solid",
                                    "width": 2
                                },
                                "opacity": 1,
                                "visible": true,
                                "xref": "x",
                                "xsizemode": "scaled",
                                "yref": "y",
                                "ysizemode": "scaled"
                            }
                        ],
                        "showlegend": false,
                        "sliders": [],
                        "spikedistance": 20,
                        "title": {
                            "font": {
                                "color": "#444",
                                "family": "\"Open Sans\", verdana, arial, sans-serif",
                                "size": 17
                            },
                            "pad": {
                                "b": 0,
                                "l": 0,
                                "r": 0,
                                "t": 0
                            },
                            "x": 0.5,
                            "xanchor": "auto",
                            "xref": "container",
                            "y": "auto",
                            "yanchor": "auto",
                            "yref": "container"
                        },
                        "updatemenus": [],
                        "width": 985.469,
                        "xaxis": {
                            "anchor": "y",
                            "automargin": false,
                            "autorange": true,
                            "categoryorder": "trace",
                            "color": "#444",
                            "constrain": "range",
                            "constraintoward": "center",
                            "domain": [
                                0,
                                1
                            ],
                            "dtick": 1,
                            "fixedrange": false,
                            "layer": "above traces",
                            "nticks": 0,
                            "range": [
                                -0.5,
                                1.5
                            ],
                            "showgrid": false,
                            "showline": false,
                            "showspikes": false,
                            "showticklabels": true,
                            "side": "bottom",
                            "tick0": 0,
                            "tickangle": "auto",
                            "tickfont": {
                                "color": "#444",
                                "family": "\"Open Sans\", verdana, arial, sans-serif",
                                "size": 12
                            },
                            "tickmode": "auto",
                            "tickprefix": "",
                            "ticks": "",
                            "ticksuffix": "",
                            "title": {
                                "font": {
                                    "color": "#444",
                                    "family": "\"Open Sans\", verdana, arial, sans-serif",
                                    "size": 14
                                },
                                "text": "Click to enter X axis title"
                            },
                            "type": "category",
                            "visible": true,
                            "zeroline": false
                        },
                        "yaxis": {
                            "anchor": "x",
                            "automargin": false,
                            "autorange": true,
                            "color": "#444",
                            "constrain": "range",
                            "constraintoward": "middle",
                            "domain": [
                                0,
                                1
                            ],
                            "dtick": 100,
                            "exponentformat": "B",
                            "fixedrange": false,
                            "gridcolor": "rgb(229, 229, 229)",
                            "gridwidth": 1,
                            "hoverformat": "",
                            "layer": "above traces",
                            "nticks": 0,
                            "range": [
                                -1.6797274275979557,
                                519.0357751277683
                            ],
                            "rangemode": "normal",
                            "separatethousands": false,
                            "showexponent": "all",
                            "showgrid": true,
                            "showline": false,
                            "showspikes": false,
                            "showticklabels": true,
                            "side": "left",
                            "tick0": 0,
                            "tickangle": "auto",
                            "tickfont": {
                                "color": "#444",
                                "family": "\"Open Sans\", verdana, arial, sans-serif",
                                "size": 12
                            },
                            "tickformat": "",
                            "tickmode": "auto",
                            "tickprefix": "",
                            "ticks": "",
                            "ticksuffix": "",
                            "title": {
                                "font": {
                                    "color": "#444",
                                    "family": "\"Open Sans\", verdana, arial, sans-serif",
                                    "size": 14
                                },
                                "text": "Click to enter Y axis title"
                            },
                            "type": "linear",
                            "visible": true,
                            "zeroline": true,
                            "zerolinecolor": "#444",
                            "zerolinewidth": 1
                        }
                    },
                    "layout_edit_id": 1
                },
                "_js2py_pointsCallback": {
                    "device_state": {
                        "alt": false,
                        "button": 0,
                        "buttons": 0,
                        "ctrl": false,
                        "meta": false,
                        "shift": false
                    },
                    "event_type": "plotly_unhover",
                    "points": {
                        "point_indexes": [
                            1
                        ],
                        "trace_indexes": [
                            0
                        ],
                        "xs": [
                            "Deposit Account"
                        ],
                        "ys": [
                            493
                        ]
                    },
                    "selector": null
                },
                "_js2py_relayout": {
                    "relayout_data": {
                        "autosize": true
                    },
                    "source_view_id": "c69b31"
                },
                "_js2py_restyle": {},
                "_js2py_traceDeltas": {
                    "trace_deltas": [
                        {
                            "alignmentgroup": "",
                            "error_x": {
                                "visible": false
                            },
                            "error_y": {
                                "visible": false
                            },
                            "hoverinfo": "x+y+z+text",
                            "hoverlabel": {
                                "align": "auto",
                                "font": {
                                    "family": "Arial, sans-serif",
                                    "size": 13
                                },
                                "namelength": 15
                            },
                            "hovertemplate": "",
                            "hovertext": "",
                            "index": 0,
                            "legendgroup": "",
                            "marker": {
                                "opacity": 1
                            },
                            "name": "trace 0",
                            "offsetgroup": "",
                            "opacity": 1,
                            "selected": {
                                "marker": {
                                    "opacity": 1
                                }
                            },
                            "showlegend": true,
                            "text": "",
                            "textposition": "none",
                            "uid": "b5f05d5b-36d8-4529-b5db-255a24f14b02",
                            "unselected": {
                                "marker": {
                                    "opacity": 0.2
                                }
                            },
                            "visible": true,
                            "xaxis": "x",
                            "xcalendar": "gregorian",
                            "yaxis": "y",
                            "ycalendar": "gregorian"
                        }
                    ],
                    "trace_edit_id": 0
                },
                "_js2py_update": {},
                "_last_layout_edit_id": 1,
                "_layout": {
                    "annotations": [
                        {
                            "font": {
                                "color": "red",
                                "size": 10
                            },
                            "showarrow": false,
                            "text": "Source: FINCEN.gov",
                            "x": 1,
                            "xanchor": "right",
                            "xref": "paper",
                            "xshift": 0,
                            "y": -0.15,
                            "yanchor": "auto",
                            "yref": "paper",
                            "yshift": 0
                        }
                    ],
                    "autosize": true,
                    "barmode": "group",
                    "hovermode": "closest",
                    "paper_bgcolor": "whitesmoke",
                    "plot_bgcolor": "whitesmoke",
                    "shapes": [
                        {
                            "line": {
                                "color": "RoyalBlue"
                            },
                            "type": "rect",
                            "x0": 0,
                            "x1": 0,
                            "y0": 0,
                            "y1": 0
                        }
                    ],
                    "template": {},
                    "title": {
                        "text": "Number SAR Filings by State and Product"
                    }
                },
                "_model_module_version": "0.9.1",
                "_py2js_addTraces": {},
                "_py2js_animate": {},
                "_py2js_deleteTraces": {},
                "_py2js_moveTraces": {},
                "_py2js_removeLayoutProps": {},
                "_py2js_removeTraceProps": {},
                "_py2js_restyle": {},
                "_py2js_update": {},
                "_view_count": 1,
                "_view_module_version": "0.9.1"
            }
        },
        "2cc8ad71b2b44f0ab9d4a6b4f15d9d32": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "2d4bb3e11d1a4e56a0852a38fb8c1317": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "2d4f211f0fe342219823e1e3ad931efd": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "2d8fdc5e196c48d9abacf7bbee2d13c2": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "2d94c8a481f547f6b76ceecbd8be8c48": {
            "model_name": "FigureModel",
            "model_module": "plotlywidget",
            "model_module_version": "0.9.1",
            "state": {
                "_config": {
                    "plotlyServerURL": "https://plot.ly"
                },
                "_data": [
                    {
                        "orientation": "v",
                        "text": "Count",
                        "textposition": "auto",
                        "type": "bar",
                        "uid": "70562be9-2d18-48f1-b02e-3ed9f96c66ab",
                        "x": [
                            "Debit Card",
                            "Deposit Account"
                        ],
                        "y": [
                            223,
                            493
                        ]
                    }
                ],
                "_js2py_pointsCallback": {},
                "_js2py_restyle": {},
                "_js2py_update": {},
                "_last_layout_edit_id": 1,
                "_layout": {
                    "annotations": [
                        {
                            "font": {
                                "color": "red",
                                "size": 10
                            },
                            "showarrow": false,
                            "text": "Source: FINCEN.gov",
                            "x": 1,
                            "xanchor": "right",
                            "xref": "paper",
                            "xshift": 0,
                            "y": -0.15,
                            "yanchor": "auto",
                            "yref": "paper",
                            "yshift": 0
                        }
                    ],
                    "autosize": true,
                    "barmode": "group",
                    "hovermode": "closest",
                    "template": {},
                    "title": {
                        "text": "SAR Filings by State and Product"
                    }
                },
                "_model_module_version": "0.9.1",
                "_py2js_addTraces": {},
                "_py2js_animate": {},
                "_py2js_deleteTraces": {},
                "_py2js_moveTraces": {},
                "_py2js_removeLayoutProps": {},
                "_py2js_removeTraceProps": {},
                "_py2js_restyle": {},
                "_py2js_update": {},
                "_view_count": 0,
                "_view_module_version": "0.9.1"
            }
        },
        "2da18d00dc6147678379c083d5da3ca1": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "2dbf7b48abe043878937676d0ca5d962": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "OCC",
                    "FDIC",
                    "SEC",
                    "FHFA",
                    "CFTC"
                ],
                "description": "Regulator :",
                "index": 0,
                "layout": "IPY_MODEL_4ac46666da1145fda46ce4d759d8c904",
                "style": "IPY_MODEL_2ffb5ec9d28f4af6b0fd1e07f4de9021"
            }
        },
        "2dca5845105f48aea6caa2d30e7ce91a": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_fe64cbb9e09d498985f08fd40dcc071e"
                ],
                "layout": "IPY_MODEL_455c03e88e2241a5af9ef094e78ff18b"
            }
        },
        "2dca726d176c4def914f3c9bada52726": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "2dce08b9c3964c79bc5714bc4496da11": {
            "model_name": "VBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_64c2e8c8af224241ade088d157e676cf",
                    "IPY_MODEL_0aec0ab592f84dffa24e052db6414d44",
                    "IPY_MODEL_f2d8a68c679541df86a7ccc0e2563d67"
                ],
                "layout": "IPY_MODEL_d7135a3e2225475c9dd01786593708f7"
            }
        },
        "2e1cf8213a4b47159f6f457b9521bac1": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "2e80fda80b98414a9e6282a54a488366": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "2e8b801e39a743d8846c7e56379d9b9f": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "2eba98d369bd42379da050cc0aba4373": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "OCC",
                    "FDIC",
                    "SEC",
                    "FHFA",
                    "CFTC"
                ],
                "description": "Regulator :",
                "index": 0,
                "layout": "IPY_MODEL_12302c1eba774d48b1fa18a666739d08",
                "style": "IPY_MODEL_50200d103b7c454db61c678dd257e61f"
            }
        },
        "2ecf827e418845d08e4f560f7b4627fb": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_f1381ffb58924c87910528c375f1150e"
                ],
                "layout": "IPY_MODEL_b9e6752fa833451ab693966964bda937"
            }
        },
        "2ed0dd38d9914fc6921e1ad23459708b": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "2ed9e3ee349a4817a37d51003dc04605": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "2ee3668abfd04ab5b037bfeb078e7371": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "2f69b9b514c24db68b9ea336f9d31b0b": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "2014",
                    "2019",
                    "2015",
                    "2018",
                    "2017",
                    "2016",
                    "2012",
                    "2013"
                ],
                "description": "Date : ",
                "index": 1,
                "layout": "IPY_MODEL_5b1bc28d0f054760ae5452ed7d211f19",
                "style": "IPY_MODEL_2906e066e889496582a65164673f1b86"
            }
        },
        "2f7a2b03a36a45059740ec5b00a99df4": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_3a8afdd109f64275921cff2dad6017d4"
                ],
                "layout": "IPY_MODEL_516358920e5f4c88b9e4307a8f3ca587"
            }
        },
        "2fc3edbdcc2b4cf58ee53e223f1f7435": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "Alabama",
                    "Arizona",
                    "Arkansas",
                    "California",
                    "Colorado",
                    "Connecticut",
                    "Delaware",
                    "District of Columbia",
                    "Florida",
                    "Georgia",
                    "Hawaii",
                    "Idaho",
                    "Illinois",
                    "Indiana",
                    "Iowa",
                    "Kansas",
                    "Kentucky",
                    "Louisiana",
                    "Maine",
                    "Maryland",
                    "Massachusetts",
                    "Michigan",
                    "Minnesota",
                    "Mississippi",
                    "Missouri",
                    "Montana",
                    "Nebraska",
                    "Nevada",
                    "New Hampshire",
                    "New Jersey",
                    "New Mexico",
                    "New York",
                    "North Carolina",
                    "North Dakota",
                    "Ohio",
                    "Oklahoma",
                    "Oregon",
                    "Pennsylvania",
                    "Puerto Rico",
                    "Rhode Island",
                    "South Carolina",
                    "South Dakota",
                    "Tennessee",
                    "Texas",
                    "Utah",
                    "Vermont",
                    "Virginia",
                    "Washington",
                    "West Virginia",
                    "Wisconsin"
                ],
                "description": "Filing State :",
                "index": 0,
                "layout": "IPY_MODEL_00a225c62edd4c62b761458374669ba3",
                "style": "IPY_MODEL_09133e00e34843b5beb50fdfe9032995"
            }
        },
        "2ffb5ec9d28f4af6b0fd1e07f4de9021": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "303b89e1de984de68ec48d59896adc37": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "308596003cc441119e1ae05a1c4bf13a": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "Alabama",
                    "Arizona",
                    "Arkansas",
                    "California",
                    "Colorado",
                    "Connecticut",
                    "Delaware",
                    "District of Columbia",
                    "Florida",
                    "Georgia",
                    "Hawaii",
                    "Idaho",
                    "Illinois",
                    "Indiana",
                    "Iowa",
                    "Kansas",
                    "Kentucky",
                    "Louisiana",
                    "Maine",
                    "Maryland",
                    "Massachusetts",
                    "Michigan",
                    "Minnesota",
                    "Mississippi",
                    "Missouri",
                    "Montana",
                    "Nebraska",
                    "Nevada",
                    "New Hampshire",
                    "New Jersey",
                    "New Mexico",
                    "New York",
                    "North Carolina",
                    "North Dakota",
                    "Ohio",
                    "Oklahoma",
                    "Oregon",
                    "Pennsylvania",
                    "Puerto Rico",
                    "Rhode Island",
                    "South Carolina",
                    "South Dakota",
                    "Tennessee",
                    "Texas",
                    "Utah",
                    "Vermont",
                    "Virginia",
                    "Washington",
                    "West Virginia",
                    "Wisconsin"
                ],
                "description": "Filing State :",
                "index": 0,
                "layout": "IPY_MODEL_863d08bac36f401898272a305db8d71e",
                "style": "IPY_MODEL_96bada15df72451596447047f3b987e1"
            }
        },
        "30980baab8fa4c558bbfd849f08ee5ea": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "30c99b1f595d4d66acf4d44f153e24ec": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "30fe764e5fbc444e98cc47dfc819492f": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_04fa5773b6ae473fb1241bfe1363f010"
                ],
                "layout": "IPY_MODEL_9d99adb14e95424aa3793f17ab36d90e"
            }
        },
        "3100705dcf534f1a9c039e39c8ea4252": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "31a5dd9c7a66461196e277e0acd01c90": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_0ea9ecccde064d39be23980e7e5e7da7"
                ],
                "layout": "IPY_MODEL_b4487b948a414e39b8f86548fb568305"
            }
        },
        "31ae502cec754851891b78c9c04ade71": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "31e32b8b94be4d3498890e7532e0c217": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "322f18565d2a4a9182c27174ac842d9a": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "32b117dd596d4bacbccbef917b5576e6": {
            "model_name": "FigureModel",
            "model_module": "plotlywidget",
            "model_module_version": "0.9.1",
            "state": {
                "_config": {
                    "plotlyServerURL": "https://plot.ly"
                },
                "_data": [
                    {
                        "marker": {
                            "color": "rgb(26, 118, 255)",
                            "line": {
                                "color": "rgba(50, 171, 96, 1.0)",
                                "width": 2
                            }
                        },
                        "orientation": "v",
                        "type": "bar",
                        "uid": "5c8ce4f0-25b0-4af7-b675-f059374e3d6d",
                        "x": [
                            "Debit Card",
                            "Deposit Account"
                        ],
                        "y": [
                            223,
                            493
                        ]
                    }
                ],
                "_js2py_restyle": {},
                "_js2py_update": {},
                "_last_layout_edit_id": 1,
                "_layout": {
                    "annotations": [
                        {
                            "font": {
                                "color": "red",
                                "size": 10
                            },
                            "showarrow": false,
                            "text": "Source: FINCEN.gov",
                            "x": 1,
                            "xanchor": "right",
                            "xref": "paper",
                            "xshift": 0,
                            "y": -0.15,
                            "yanchor": "auto",
                            "yref": "paper",
                            "yshift": 0
                        }
                    ],
                    "autosize": true,
                    "barmode": "group",
                    "hovermode": "closest",
                    "template": {},
                    "title": {
                        "text": "SAR Filings by State and Product"
                    }
                },
                "_model_module_version": "0.9.1",
                "_py2js_addTraces": {},
                "_py2js_animate": {},
                "_py2js_deleteTraces": {},
                "_py2js_moveTraces": {},
                "_py2js_removeLayoutProps": {},
                "_py2js_removeTraceProps": {},
                "_py2js_restyle": {},
                "_py2js_update": {},
                "_view_count": 0,
                "_view_module_version": "0.9.1"
            }
        },
        "32b689e098b34b7bbf3c558375bf55f2": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "32bdff366dd64cf19f82055534232729": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "32ddd6272af2480a8ef0a5c112dfac21": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "332488ae57004e7a9f2f3cee17b15ae5": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "333255d236f040219e9f0bbe8d6b8dbe": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "2014",
                    "2019",
                    "2015",
                    "2018",
                    "2017",
                    "2016",
                    "2012",
                    "2013"
                ],
                "description": "Date : ",
                "index": 1,
                "layout": "IPY_MODEL_cf3131e90e594962b0d9280065b8a7a7",
                "style": "IPY_MODEL_8e519461e1874731a7d77172423e4cfe"
            }
        },
        "334dc05a00be4fa1bce3ee9141ee5b20": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "334fa97fe0e34f72b988a78cd8fc99ba": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "33757f176cff48a39222bd4672091c97": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "2014",
                    "2019",
                    "2015",
                    "2018",
                    "2017",
                    "2016",
                    "2012",
                    "2013"
                ],
                "description": "Date : ",
                "index": 1,
                "layout": "IPY_MODEL_7baaf4e317cc46838f0d3b2a5e898f88",
                "style": "IPY_MODEL_b01ad2e904fc459394e1241799449419"
            }
        },
        "337e40e1d834427a829fad80c113f973": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_af41d7e3fe4e46efbbc44f0d84bee51e"
                ],
                "layout": "IPY_MODEL_a67732a11b5240e1bfe33bff0ef219f6"
            }
        },
        "3396e7ecd97d41d3908cbcc0c58d2dba": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "OCC",
                    "FDIC",
                    "SEC",
                    "FHFA",
                    "CFTC"
                ],
                "description": "Regulator :",
                "index": 0,
                "layout": "IPY_MODEL_a89299d078364542b3926e1bb23890d1",
                "style": "IPY_MODEL_f579d2ab060545938bcb69f1896c1a54"
            }
        },
        "33a877cf33804baeb3b44113399c6fee": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "Alabama",
                    "Arizona",
                    "Arkansas",
                    "California",
                    "Colorado",
                    "Connecticut",
                    "Delaware",
                    "District of Columbia",
                    "Florida",
                    "Georgia",
                    "Hawaii",
                    "Idaho",
                    "Illinois",
                    "Indiana",
                    "Iowa",
                    "Kansas",
                    "Kentucky",
                    "Louisiana",
                    "Maine",
                    "Maryland",
                    "Massachusetts",
                    "Michigan",
                    "Minnesota",
                    "Mississippi",
                    "Missouri",
                    "Montana",
                    "Nebraska",
                    "Nevada",
                    "New Hampshire",
                    "New Jersey",
                    "New Mexico",
                    "New York",
                    "North Carolina",
                    "North Dakota",
                    "Ohio",
                    "Oklahoma",
                    "Oregon",
                    "Pennsylvania",
                    "Puerto Rico",
                    "Rhode Island",
                    "South Carolina",
                    "South Dakota",
                    "Tennessee",
                    "Texas",
                    "Utah",
                    "Vermont",
                    "Virginia",
                    "Washington",
                    "West Virginia",
                    "Wisconsin"
                ],
                "description": "Filing State :",
                "index": 0,
                "layout": "IPY_MODEL_bfff78cc6b224d1da64d2ae1067d5a26",
                "style": "IPY_MODEL_f18bb5a7ec9f417a9e35688dfb74f9a8"
            }
        },
        "33be9aaa6fda43fab2de849440794b3d": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_7061cc2d40a74efa90a825adefd5b54c",
                    "IPY_MODEL_6e69c07747cb41de88b0525cbead06af"
                ],
                "layout": "IPY_MODEL_34e90cf9de2a41f882ed54693a2b7d3b"
            }
        },
        "33c2db90cafc43c8ba7cf3c740a63874": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "3477aad2536342c5990d78e4950bda34": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "OCC",
                    "FDIC",
                    "SEC",
                    "FHFA",
                    "CFTC"
                ],
                "description": "Regulator :",
                "index": 0,
                "layout": "IPY_MODEL_e75ddef53ea2452a8285d88f98c7a3ab",
                "style": "IPY_MODEL_75ec67aaf02f43c0a154c5f8b236b336"
            }
        },
        "347bdb2cdc564b29a3c676ab4a8ad714": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_aab5cae53ffd4d58a20512fd4fb2b3c0"
                ],
                "layout": "IPY_MODEL_cc185409b4a44f3ba8cac365ac62f045"
            }
        },
        "34826e38e7e9468b8ab2e75fa19cae12": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "34a6bf1c7eba46c7bed601b6f9fb9663": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "34bf250be06242638e6b9d2f423e1233": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "OCC",
                    "FDIC",
                    "SEC",
                    "FHFA",
                    "CFTC"
                ],
                "description": "Regulator :",
                "index": 0,
                "layout": "IPY_MODEL_c01533267352417bbe6e407e0cb8fd1a",
                "style": "IPY_MODEL_3100705dcf534f1a9c039e39c8ea4252"
            }
        },
        "34daa25565014c5a933824d0c536d38e": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_f7d2cc10afe34c9897b23f14db8e0419"
                ],
                "layout": "IPY_MODEL_b98cb6367cb74a1899db9020b4267596"
            }
        },
        "34e90cf9de2a41f882ed54693a2b7d3b": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "3504d3ef2391481798021a35890efe95": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "OCC",
                    "FDIC",
                    "SEC",
                    "FHFA",
                    "CFTC"
                ],
                "description": "Regulator :",
                "index": 0,
                "layout": "IPY_MODEL_4eeb9b45e09f4e28a23cf8edb9e2c418",
                "style": "IPY_MODEL_eee845c0882d4ea9ad470452c9704454"
            }
        },
        "352f174550d44aa18ed15e1d6a9345c9": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "354a7dc97b8b43fc820e99b1ea11875e": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "355d947b71534aa1bce446dad8c9e557": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "35ad72028cf74ba6a747615d04bacbbf": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "35ec63c844e3440e9fffeeafde981f7e": {
            "model_name": "VBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_5afdc52fde0449b1908b4da5a2074ab9",
                    "IPY_MODEL_48a086ae90eb47ebb991a02c53fec9f0",
                    "IPY_MODEL_f33f22da270e413b961e2674eeb8fba0"
                ],
                "layout": "IPY_MODEL_0727a5c642304646b983f9c96d15e4dc"
            }
        },
        "369c031861bf468cb31146311ae67a58": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "369d01035d584ee08a84c09fe23de0bc": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "36a764f9e2bf4485bc2df21f747bdeae": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "36bf0002b54f490a9678dca70636ab76": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "Alabama",
                    "Arizona",
                    "Arkansas",
                    "California",
                    "Colorado",
                    "Connecticut",
                    "Delaware",
                    "District of Columbia",
                    "Florida",
                    "Georgia",
                    "Hawaii",
                    "Idaho",
                    "Illinois",
                    "Indiana",
                    "Iowa",
                    "Kansas",
                    "Kentucky",
                    "Louisiana",
                    "Maine",
                    "Maryland",
                    "Massachusetts",
                    "Michigan",
                    "Minnesota",
                    "Mississippi",
                    "Missouri",
                    "Montana",
                    "Nebraska",
                    "Nevada",
                    "New Hampshire",
                    "New Jersey",
                    "New Mexico",
                    "New York",
                    "North Carolina",
                    "North Dakota",
                    "Ohio",
                    "Oklahoma",
                    "Oregon",
                    "Pennsylvania",
                    "Puerto Rico",
                    "Rhode Island",
                    "South Carolina",
                    "South Dakota",
                    "Tennessee",
                    "Texas",
                    "Utah",
                    "Vermont",
                    "Virginia",
                    "Washington",
                    "West Virginia",
                    "Wisconsin"
                ],
                "description": "Filing State :",
                "index": 0,
                "layout": "IPY_MODEL_0991ca0e4efc46148f92454a06b833e9",
                "style": "IPY_MODEL_eed62db92bc24083aa25f640e90da6c9"
            }
        },
        "36de34e1dac14d6bb452cf6daeb725a0": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_48161433e8324871a1c8e22b1dec6193"
                ],
                "layout": "IPY_MODEL_d0aee662ab344d329005a226688bb0e7"
            }
        },
        "3704572d8582420c889dff4a67547155": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "3731e648613e482590ccc0934d0f75bb": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "37f5e8d6c3f74f9ab260173a29140c73": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "3806290d829749ef90600b5596851b2e": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "3826ebbaf1324939bab3e866a5d88fe8": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "2014",
                    "2019",
                    "2015",
                    "2018",
                    "2017",
                    "2016",
                    "2012",
                    "2013"
                ],
                "description": "Date : ",
                "index": 1,
                "layout": "IPY_MODEL_e70cd3dafdcb405bb5a89e63dfd2b03f",
                "style": "IPY_MODEL_b3152bc095ca4ea6b2de7f6b59f6a9b9"
            }
        },
        "38ac83726b064afab433dddd28ae0dc1": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "Alabama",
                    "Arizona",
                    "Arkansas",
                    "California",
                    "Colorado",
                    "Connecticut",
                    "Delaware",
                    "District of Columbia",
                    "Florida",
                    "Georgia",
                    "Hawaii",
                    "Idaho",
                    "Illinois",
                    "Indiana",
                    "Iowa",
                    "Kansas",
                    "Kentucky",
                    "Louisiana",
                    "Maine",
                    "Maryland",
                    "Massachusetts",
                    "Michigan",
                    "Minnesota",
                    "Mississippi",
                    "Missouri",
                    "Montana",
                    "Nebraska",
                    "Nevada",
                    "New Hampshire",
                    "New Jersey",
                    "New Mexico",
                    "New York",
                    "North Carolina",
                    "North Dakota",
                    "Ohio",
                    "Oklahoma",
                    "Oregon",
                    "Pennsylvania",
                    "Puerto Rico",
                    "Rhode Island",
                    "South Carolina",
                    "South Dakota",
                    "Tennessee",
                    "Texas",
                    "Utah",
                    "Vermont",
                    "Virginia",
                    "Washington",
                    "West Virginia",
                    "Wisconsin"
                ],
                "description": "Filing State :",
                "index": 0,
                "layout": "IPY_MODEL_1ef03151fee3473ba9fb0dccd0465aed",
                "style": "IPY_MODEL_d99f1adff64442c7b7204152ab515b24"
            }
        },
        "39108128d2a54c3da22972d2a3d98477": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "3915ada25de547bf9918d043dd4faa68": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "393ba43dcb85416e8017feaa68d5efda": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_40a3db19acd643f79fc4b3f294b79a54"
                ],
                "layout": "IPY_MODEL_a798f4078c794cdd8830148d401bf134"
            }
        },
        "395e5f72be924356871df049f2bfd4b9": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "396ee1b489af4cbdae7475c5a2b5204e": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "39971ca2602542f9a6829794b9ff07a6": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "OCC",
                    "FDIC",
                    "SEC",
                    "FHFA",
                    "CFTC"
                ],
                "description": "Regulator :",
                "index": 0,
                "layout": "IPY_MODEL_2dca726d176c4def914f3c9bada52726",
                "style": "IPY_MODEL_1076af3152fd400684dcf83c7bdb1aea"
            }
        },
        "3998c82e4cb448898f5db1b861d80c01": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "39a7c41e3395411eb18e2194f09ebe6d": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "39cd31d0bc5c447c8b3a27187e827a18": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "39cea490c8d4483bb6a12b4232e10bbe": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "3a14373c744e4317a0fee5bda4570158": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "3a3a5b33297f46a4b0c45882740c3b1a": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "3a7eb3d892ad438395b3f58ec16cd5c1": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "3a81b61e5feb4925b58d426db0a404e1": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "3a8afdd109f64275921cff2dad6017d4": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "2014",
                    "2019",
                    "2015",
                    "2018",
                    "2017",
                    "2016",
                    "2012",
                    "2013"
                ],
                "description": "Date : ",
                "index": 1,
                "layout": "IPY_MODEL_fcd489a197cc4f37bf1d237b19f49c28",
                "style": "IPY_MODEL_e79e4f02d509422c929d72ddca10976b"
            }
        },
        "3abd5898c1b34824bb2fac6383283afa": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "2014",
                    "2019",
                    "2015",
                    "2018",
                    "2017",
                    "2016",
                    "2012",
                    "2013"
                ],
                "description": "Date : ",
                "index": 1,
                "layout": "IPY_MODEL_ea715a0e04fb446b8bd289f5aeae8a3f",
                "style": "IPY_MODEL_0e3c61bc4f194d98961ae09c9b698e90"
            }
        },
        "3ac37786169f4010aec1f6cce80ca59b": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "3aea042089ae4675adcc0cd4c67527dc": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "3aeb9c254c554c7aba6c230493cefdb4": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_0427a4a741034461bbdf20fd0def9d0a"
                ],
                "layout": "IPY_MODEL_e902dbd3dfc8414bb25fbc1ef618b0dd"
            }
        },
        "3af5398c371e494ca549bf12714176bc": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "3b3d77574e5e4870b89662cab647c13b": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "3b3de6fa5b19437f8c640de8b9ded12e": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "3b40896889564991a21e058ecc1e3665": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "3b8bd3247aa744068dcde644537a1f7c": {
            "model_name": "VBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_feb55d41528947fd993e16671bad93c8",
                    "IPY_MODEL_c7178376c27e491d8373fa6e16ba34dd",
                    "IPY_MODEL_2d94c8a481f547f6b76ceecbd8be8c48"
                ],
                "layout": "IPY_MODEL_8247ea68c4be4a76b7a77eacbf65c8cb"
            }
        },
        "3bbc07357a3c4e739d9ffa2953109c1a": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_928178ea30c44c25b711d7a790cafad4"
                ],
                "layout": "IPY_MODEL_ab2066d0c65247808ea4725f17e76bc6"
            }
        },
        "3bbea1f47e494769891c6f3457133451": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "3bce96798f7a4d29b7f90b0cb3bced09": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "3c30c87bca7243508196f83858af9147": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "3c3e65732aee42a692da7e60570bfce8": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "3c51345f35114f35a54fc4f4d3ba0fbb": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "2014",
                    "2019",
                    "2015",
                    "2018",
                    "2017",
                    "2016",
                    "2012",
                    "2013"
                ],
                "description": "Date : ",
                "index": 1,
                "layout": "IPY_MODEL_b04fa3242e4d42b7bd815910fc2eaf3f",
                "style": "IPY_MODEL_1a536be7a13d496db6770f2cd4f6463d"
            }
        },
        "3c5b91a928894f9294c87fd91ecb1b7b": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "2014",
                    "2019",
                    "2015",
                    "2018",
                    "2017",
                    "2016",
                    "2012",
                    "2013"
                ],
                "description": "Date : ",
                "index": 1,
                "layout": "IPY_MODEL_06fe23c2cdde486b9e8209f949986c34",
                "style": "IPY_MODEL_10fc913a807640aa92d10f38a8a76e8f"
            }
        },
        "3c8bd760910d498295175fd99775ee45": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "2014",
                    "2019",
                    "2015",
                    "2018",
                    "2017",
                    "2016",
                    "2012",
                    "2013"
                ],
                "description": "Date : ",
                "index": 1,
                "layout": "IPY_MODEL_449428a30c824c919fa201db1cdb4b72",
                "style": "IPY_MODEL_4d16e68b06a14b3abbe4a1b4a4dd43cf"
            }
        },
        "3cd112c5bd954c448b12344d98c630f3": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "3d168e4fed5a45dba5e6142a590c1485": {
            "model_name": "VBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_96b9df678a1144219019abe4036e0699",
                    "IPY_MODEL_85a25e88a71140b8ba4a7b7c94db2217",
                    "IPY_MODEL_0a5338114e824313b5dd8a142ea87f35"
                ],
                "layout": "IPY_MODEL_ac806ab9064545d3adc396ac486cf154"
            }
        },
        "3d1a9e5fc86b4b0986bccd6c5b37020d": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "Alabama",
                    "Arizona",
                    "Arkansas",
                    "California",
                    "Colorado",
                    "Connecticut",
                    "Delaware",
                    "District of Columbia",
                    "Florida",
                    "Georgia",
                    "Hawaii",
                    "Idaho",
                    "Illinois",
                    "Indiana",
                    "Iowa",
                    "Kansas",
                    "Kentucky",
                    "Louisiana",
                    "Maine",
                    "Maryland",
                    "Massachusetts",
                    "Michigan",
                    "Minnesota",
                    "Mississippi",
                    "Missouri",
                    "Montana",
                    "Nebraska",
                    "Nevada",
                    "New Hampshire",
                    "New Jersey",
                    "New Mexico",
                    "New York",
                    "North Carolina",
                    "North Dakota",
                    "Ohio",
                    "Oklahoma",
                    "Oregon",
                    "Pennsylvania",
                    "Puerto Rico",
                    "Rhode Island",
                    "South Carolina",
                    "South Dakota",
                    "Tennessee",
                    "Texas",
                    "Utah",
                    "Vermont",
                    "Virginia",
                    "Washington",
                    "West Virginia",
                    "Wisconsin"
                ],
                "description": "Filing State :",
                "index": 0,
                "layout": "IPY_MODEL_e529cb2fb5e945bdb5f79eca27dae8da",
                "style": "IPY_MODEL_cfee4acfaae948969089237ed9104d2b"
            }
        },
        "3d74aeaede3d4cd381fb4d1522efa834": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "3da1a967acad4f56ac2dd3b61f6e1754": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "3dcd196670324c1ea1776ee53448ff5f": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_4dfc48662b2f444b9fd0d5631429fffc",
                    "IPY_MODEL_f08f9dff66c14e7cb2ddfe9ecffa4b52"
                ],
                "layout": "IPY_MODEL_0d440d4e3640489094c2b70d9678f146"
            }
        },
        "3ddfdee0c5ed438eb7cc4660b3f156a7": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "3de450af77744ffe95db0cbd8c7c1295": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "3f150c57b53c4da5b4b06337c1db033f": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "3fa3f2257eb9448d8144db1ffc871540": {
            "model_name": "FigureModel",
            "model_module": "plotlywidget",
            "model_module_version": "0.9.1",
            "state": {
                "_config": {
                    "plotlyServerURL": "https://plot.ly"
                },
                "_data": [
                    {
                        "marker": {
                            "color": "rgb(26, 118, 255)",
                            "line": {
                                "color": "rgba(100, 118, 255, 1.0)",
                                "width": 2
                            }
                        },
                        "orientation": "v",
                        "type": "bar",
                        "uid": "d0d5dd56-c5d3-4576-9e10-a4075259cc1f",
                        "x": [
                            "Debit Card",
                            "Deposit Account"
                        ],
                        "y": [
                            223,
                            493
                        ]
                    }
                ],
                "_js2py_pointsCallback": {},
                "_js2py_restyle": {},
                "_js2py_update": {},
                "_last_layout_edit_id": 1,
                "_layout": {
                    "annotations": [
                        {
                            "font": {
                                "color": "red",
                                "size": 10
                            },
                            "showarrow": false,
                            "text": "Source: FINCEN.gov",
                            "x": 1,
                            "xanchor": "right",
                            "xref": "paper",
                            "xshift": 0,
                            "y": -0.15,
                            "yanchor": "auto",
                            "yref": "paper",
                            "yshift": 0
                        }
                    ],
                    "autosize": true,
                    "barmode": "group",
                    "hovermode": "closest",
                    "template": {},
                    "title": {
                        "text": "SAR Filings by State and Product"
                    }
                },
                "_model_module_version": "0.9.1",
                "_py2js_addTraces": {},
                "_py2js_animate": {},
                "_py2js_deleteTraces": {},
                "_py2js_moveTraces": {},
                "_py2js_removeLayoutProps": {},
                "_py2js_removeTraceProps": {},
                "_py2js_restyle": {},
                "_py2js_update": {},
                "_view_count": 0,
                "_view_module_version": "0.9.1"
            }
        },
        "3fc51500c714461bbde743bdd289df4d": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "3fcf39c849cb46a4ba4d533f799c8f07": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "3fefff7268b5438791967a8a9c539106": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "Alabama",
                    "Arizona",
                    "Arkansas",
                    "California",
                    "Colorado",
                    "Connecticut",
                    "Delaware",
                    "District of Columbia",
                    "Florida",
                    "Georgia",
                    "Hawaii",
                    "Idaho",
                    "Illinois",
                    "Indiana",
                    "Iowa",
                    "Kansas",
                    "Kentucky",
                    "Louisiana",
                    "Maine",
                    "Maryland",
                    "Massachusetts",
                    "Michigan",
                    "Minnesota",
                    "Mississippi",
                    "Missouri",
                    "Montana",
                    "Nebraska",
                    "Nevada",
                    "New Hampshire",
                    "New Jersey",
                    "New Mexico",
                    "New York",
                    "North Carolina",
                    "North Dakota",
                    "Ohio",
                    "Oklahoma",
                    "Oregon",
                    "Pennsylvania",
                    "Puerto Rico",
                    "Rhode Island",
                    "South Carolina",
                    "South Dakota",
                    "Tennessee",
                    "Texas",
                    "Utah",
                    "Vermont",
                    "Virginia",
                    "Washington",
                    "West Virginia",
                    "Wisconsin"
                ],
                "description": "Filing State :",
                "index": 0,
                "layout": "IPY_MODEL_c353c1215cdc4b368d8b8a41ee39b566",
                "style": "IPY_MODEL_5ace3d001e7546849ec15b60a10f65be"
            }
        },
        "405d62cb020d4e828d67c7775e130826": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "40a3db19acd643f79fc4b3f294b79a54": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "2014",
                    "2019",
                    "2015",
                    "2018",
                    "2017",
                    "2016",
                    "2012",
                    "2013"
                ],
                "description": "Date : ",
                "index": 1,
                "layout": "IPY_MODEL_170b2bf62a1e478aa80a292fc41eb4ce",
                "style": "IPY_MODEL_f3e70adbcc2349ae8f2d77950544f0b7"
            }
        },
        "40e88970e4274adf8b9f8f70724f77b8": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "40f19cdf17f644c59653a9b9e1c3fb8c": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "416926855ab44d64a9269afbb0df257c": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "2014",
                    "2019",
                    "2015",
                    "2018",
                    "2017",
                    "2016",
                    "2012",
                    "2013"
                ],
                "description": "Date : ",
                "index": 1,
                "layout": "IPY_MODEL_c147a9a5a3474ebc923306484925b93f",
                "style": "IPY_MODEL_e0296cb3f22a4023ae3f5d28896e449a"
            }
        },
        "419884c76d274d89a6ac82593ba28527": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "42b6dc9d104649f8a05212d47377b16e": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "42b770201ee5486db2c0feb654f960e0": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "43790e4eb2d142b9a18ae3decbe7e2d0": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "2014",
                    "2019",
                    "2015",
                    "2018",
                    "2017",
                    "2016",
                    "2012",
                    "2013"
                ],
                "description": "Date : ",
                "index": 1,
                "layout": "IPY_MODEL_1eb6a95e13b447228c719c650ddecf57",
                "style": "IPY_MODEL_8b52292ac991442ab746cccd0eaaa254"
            }
        },
        "43b74c70e6ce41bcb6f967fd5ce509c5": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_dce04276b76b481d8aed78abf4d6b5c2"
                ],
                "layout": "IPY_MODEL_f219f198e6484fd7b9b582cb176592ae"
            }
        },
        "43d70abf655f4a808f971be63189afdd": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "4410e038b3b14b07b13708a1dfd5a820": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "Alabama",
                    "Arizona",
                    "Arkansas",
                    "California",
                    "Colorado",
                    "Connecticut",
                    "Delaware",
                    "District of Columbia",
                    "Florida",
                    "Georgia",
                    "Hawaii",
                    "Idaho",
                    "Illinois",
                    "Indiana",
                    "Iowa",
                    "Kansas",
                    "Kentucky",
                    "Louisiana",
                    "Maine",
                    "Maryland",
                    "Massachusetts",
                    "Michigan",
                    "Minnesota",
                    "Mississippi",
                    "Missouri",
                    "Montana",
                    "Nebraska",
                    "Nevada",
                    "New Hampshire",
                    "New Jersey",
                    "New Mexico",
                    "New York",
                    "North Carolina",
                    "North Dakota",
                    "Ohio",
                    "Oklahoma",
                    "Oregon",
                    "Pennsylvania",
                    "Puerto Rico",
                    "Rhode Island",
                    "South Carolina",
                    "South Dakota",
                    "Tennessee",
                    "Texas",
                    "Utah",
                    "Vermont",
                    "Virginia",
                    "Washington",
                    "West Virginia",
                    "Wisconsin"
                ],
                "description": "Filing State :",
                "index": 0,
                "layout": "IPY_MODEL_06225ad1facd41cbacbf5280a62cf5f0",
                "style": "IPY_MODEL_02472ded8bb149bfbbd665bc504d5e52"
            }
        },
        "449428a30c824c919fa201db1cdb4b72": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "44e932d2cba54098a173826cffe158a1": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "455c03e88e2241a5af9ef094e78ff18b": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "4579647012c64433891268ed654bd5df": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "459ad405e8cd4178b75c1efb58124ce2": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "459e3a280cb649f0b3128bd2211cab64": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "2014",
                    "2019",
                    "2015",
                    "2018",
                    "2017",
                    "2016",
                    "2012",
                    "2013"
                ],
                "description": "Date : ",
                "index": 1,
                "layout": "IPY_MODEL_21e8a332e1c547ac8fd317f9b2bdd9b2",
                "style": "IPY_MODEL_b0e38bfaf7294ea7b0e758da26bf0a0f"
            }
        },
        "45b7a107bfa743398dbc038f250c2d20": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "45f48e9594074e4c807b9bf2199ad38d": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "4624452a77a64219bddf51a10d1e8d36": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "OCC",
                    "FDIC",
                    "SEC",
                    "FHFA",
                    "CFTC"
                ],
                "description": "Regulator :",
                "index": 0,
                "layout": "IPY_MODEL_db97d7e7684e44a4845a9b8dcbab80b4",
                "style": "IPY_MODEL_7a8a2adddea640a5a361984f9aa7c59d"
            }
        },
        "463b9151b0c04c5ba54f815cd33018f2": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "4663ca64e37e4b24ad5487e40d50cbb4": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "46a034e053a54e81b9863c4bb0e75d8b": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_fc2482ab75b944b9a8c43f65daa91e5e"
                ],
                "layout": "IPY_MODEL_463b9151b0c04c5ba54f815cd33018f2"
            }
        },
        "46a18fcaba4b4cfd9e06d016133ef74c": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "Alabama",
                    "Arizona",
                    "Arkansas",
                    "California",
                    "Colorado",
                    "Connecticut",
                    "Delaware",
                    "District of Columbia",
                    "Florida",
                    "Georgia",
                    "Hawaii",
                    "Idaho",
                    "Illinois",
                    "Indiana",
                    "Iowa",
                    "Kansas",
                    "Kentucky",
                    "Louisiana",
                    "Maine",
                    "Maryland",
                    "Massachusetts",
                    "Michigan",
                    "Minnesota",
                    "Mississippi",
                    "Missouri",
                    "Montana",
                    "Nebraska",
                    "Nevada",
                    "New Hampshire",
                    "New Jersey",
                    "New Mexico",
                    "New York",
                    "North Carolina",
                    "North Dakota",
                    "Ohio",
                    "Oklahoma",
                    "Oregon",
                    "Pennsylvania",
                    "Puerto Rico",
                    "Rhode Island",
                    "South Carolina",
                    "South Dakota",
                    "Tennessee",
                    "Texas",
                    "Utah",
                    "Vermont",
                    "Virginia",
                    "Washington",
                    "West Virginia",
                    "Wisconsin"
                ],
                "description": "Filing State :",
                "index": 0,
                "layout": "IPY_MODEL_ead9d51d000e4f95b4f7bdc8e104f4b8",
                "style": "IPY_MODEL_ae244d7ee6e94bc5935daebfc7c90abd"
            }
        },
        "46be0f6e29fb407d90d8ebfa4f24e856": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "474a1d82ab824b1ab57496947f83a48f": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "477ff576f91e4545b50d0d8d6403ed08": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "47a3eff975c84dee8bebf1802655a793": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "4810aeb74b1a43cab93c9309dd200424": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "48161433e8324871a1c8e22b1dec6193": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "2014",
                    "2019",
                    "2015",
                    "2018",
                    "2017",
                    "2016",
                    "2012",
                    "2013"
                ],
                "description": "Date : ",
                "index": 1,
                "layout": "IPY_MODEL_72ce4bd63f104f2697fc53f642a242e0",
                "style": "IPY_MODEL_74d4c7c110ae451a8bb7bf5592990e7c"
            }
        },
        "482f5398d9e546b8a5eec4ccc35b71e4": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "48422787b3094a2e9e4c222db2f39dc4": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "OCC",
                    "FDIC",
                    "SEC",
                    "FHFA",
                    "CFTC"
                ],
                "description": "Regulator :",
                "index": 0,
                "layout": "IPY_MODEL_ebed06ca34174517b27757643ce400b8",
                "style": "IPY_MODEL_aa1eb2cb55c644788ea2c123ac094d58"
            }
        },
        "487ee3a70bef40f8996896d2769e7dfa": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "488a0871a7e54cf6a13de72f0143001d": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "OCC",
                    "FDIC",
                    "SEC",
                    "FHFA",
                    "CFTC"
                ],
                "description": "Regulator :",
                "index": 0,
                "layout": "IPY_MODEL_d2d768fb1a724e869540ccca4f16c6cf",
                "style": "IPY_MODEL_2ae6b740c08648d8a6e94b0dc64877fd"
            }
        },
        "48a086ae90eb47ebb991a02c53fec9f0": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_b623594e6f704746810dfb86ea58f627",
                    "IPY_MODEL_4954f772f5f04312aeb80b13e3b4e158"
                ],
                "layout": "IPY_MODEL_aa329f450d7b4f7191363a97c1f19878"
            }
        },
        "48a689b115694e2b8a7ca849a08564b7": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "48d77198104e43879e0bf758f5df852f": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "2014",
                    "2019",
                    "2015",
                    "2018",
                    "2017",
                    "2016",
                    "2012",
                    "2013"
                ],
                "description": "Date : ",
                "index": 1,
                "layout": "IPY_MODEL_b2ade52b17724facb03a81738bb2519b",
                "style": "IPY_MODEL_9169f640f28d4ec7b5524a8b06431313"
            }
        },
        "4951eba8ee004057bdcb7e35fd5ba90c": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "2014",
                    "2019",
                    "2015",
                    "2018",
                    "2017",
                    "2016",
                    "2012",
                    "2013"
                ],
                "description": "Date : ",
                "index": 1,
                "layout": "IPY_MODEL_4d2407d3ef6f41b8b4b3a7824a88fa39",
                "style": "IPY_MODEL_ba0aaa81960d48e8a9e149e5fbdebbc1"
            }
        },
        "4954f772f5f04312aeb80b13e3b4e158": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "OCC",
                    "FDIC",
                    "SEC",
                    "FHFA",
                    "CFTC"
                ],
                "description": "Regulator :",
                "index": 0,
                "layout": "IPY_MODEL_9f54c61112a64be299c79d1d491de9d8",
                "style": "IPY_MODEL_e14bbfd71f24439d827c7f77e8d01963"
            }
        },
        "4a29b23d8fe74a47b98331081a5a934b": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "4a33da1c38e3436588d0ae70411fe35b": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "4a3b2cea94684b68a331a52a504d32cd": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "4a76acbef54f4fed97d4e39693a8cf6b": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "4ac46666da1145fda46ce4d759d8c904": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "4aeed3d15eb747e39c09b2ac0fe9ebc1": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "OCC",
                    "FDIC",
                    "SEC",
                    "FHFA",
                    "CFTC"
                ],
                "description": "Regulator :",
                "index": 0,
                "layout": "IPY_MODEL_a61bb716b4d04eceb46c3f89ee81f6b9",
                "style": "IPY_MODEL_9f61922450eb493880e53c2048827aa9"
            }
        },
        "4af2eda0e1154c3b99651872fdb4d2f9": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "4b3736e4283b49b9b08b1deffc9e9acc": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "OCC",
                    "FDIC",
                    "SEC",
                    "FHFA",
                    "CFTC"
                ],
                "description": "Regulator :",
                "index": 0,
                "layout": "IPY_MODEL_7a49cf26a9204a49b525571e541cd8aa",
                "style": "IPY_MODEL_899e3d1001a446eaa7e5bb0a35c05f54"
            }
        },
        "4b4b08cb21154f6bb8ceecc24839f61b": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "2014",
                    "2019",
                    "2015",
                    "2018",
                    "2017",
                    "2016",
                    "2012",
                    "2013"
                ],
                "description": "Date : ",
                "index": 1,
                "layout": "IPY_MODEL_44e932d2cba54098a173826cffe158a1",
                "style": "IPY_MODEL_ddcb946a4ba54c78b043641522437a04"
            }
        },
        "4b7d055de5664b3bbcdd5df7fff46e84": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "4bb0b80c3b8948298947792638b0b10c": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "4c0c98e646964689bd6c577844c6becd": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "Alabama",
                    "Arizona",
                    "Arkansas",
                    "California",
                    "Colorado",
                    "Connecticut",
                    "Delaware",
                    "District of Columbia",
                    "Florida",
                    "Georgia",
                    "Hawaii",
                    "Idaho",
                    "Illinois",
                    "Indiana",
                    "Iowa",
                    "Kansas",
                    "Kentucky",
                    "Louisiana",
                    "Maine",
                    "Maryland",
                    "Massachusetts",
                    "Michigan",
                    "Minnesota",
                    "Mississippi",
                    "Missouri",
                    "Montana",
                    "Nebraska",
                    "Nevada",
                    "New Hampshire",
                    "New Jersey",
                    "New Mexico",
                    "New York",
                    "North Carolina",
                    "North Dakota",
                    "Ohio",
                    "Oklahoma",
                    "Oregon",
                    "Pennsylvania",
                    "Puerto Rico",
                    "Rhode Island",
                    "South Carolina",
                    "South Dakota",
                    "Tennessee",
                    "Texas",
                    "Utah",
                    "Vermont",
                    "Virginia",
                    "Washington",
                    "West Virginia",
                    "Wisconsin"
                ],
                "description": "Filing State :",
                "index": 0,
                "layout": "IPY_MODEL_eb903587316d4ba58b98236a80f19d18",
                "style": "IPY_MODEL_8f090569de674a4db7138ac41fb166ed"
            }
        },
        "4c6066165991458f9d86ba3a3a8c75e6": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "4c6115c691b9400bb9b1b7e17fce2be7": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "4c84f06a7c63428597fea0f2f11e743a": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "4cddf069cfeb4407a8973ad2772c0f61": {
            "model_name": "VBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_fa8d963946fe40ada4d32710f5467d2f",
                    "IPY_MODEL_d15a770f633e403ca70ff29b06fe28a1",
                    "IPY_MODEL_5fdea2bcadc14936b435a5c6b56cad84"
                ],
                "layout": "IPY_MODEL_78aa9f61def741a4ba2a8f3e10e3f89c"
            }
        },
        "4cf5b9366259456d8ce51f431d6b7e0a": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "4d10a323ab704d5d9bfaa137884a5067": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "Alabama",
                    "Arizona",
                    "Arkansas",
                    "California",
                    "Colorado",
                    "Connecticut",
                    "Delaware",
                    "District of Columbia",
                    "Florida",
                    "Georgia",
                    "Hawaii",
                    "Idaho",
                    "Illinois",
                    "Indiana",
                    "Iowa",
                    "Kansas",
                    "Kentucky",
                    "Louisiana",
                    "Maine",
                    "Maryland",
                    "Massachusetts",
                    "Michigan",
                    "Minnesota",
                    "Mississippi",
                    "Missouri",
                    "Montana",
                    "Nebraska",
                    "Nevada",
                    "New Hampshire",
                    "New Jersey",
                    "New Mexico",
                    "New York",
                    "North Carolina",
                    "North Dakota",
                    "Ohio",
                    "Oklahoma",
                    "Oregon",
                    "Pennsylvania",
                    "Puerto Rico",
                    "Rhode Island",
                    "South Carolina",
                    "South Dakota",
                    "Tennessee",
                    "Texas",
                    "Utah",
                    "Vermont",
                    "Virginia",
                    "Washington",
                    "West Virginia",
                    "Wisconsin"
                ],
                "description": "Filing State :",
                "index": 0,
                "layout": "IPY_MODEL_aa02ce9037cf4ba7a1f2fda215165325",
                "style": "IPY_MODEL_837ac0e944654a2f902e6aec465a5769"
            }
        },
        "4d16e68b06a14b3abbe4a1b4a4dd43cf": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "4d2407d3ef6f41b8b4b3a7824a88fa39": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "4d4d830f26584bb19d691533fac20bb8": {
            "model_name": "VBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_14d96d28a7de4386aa9a9e9deb8ee60c",
                    "IPY_MODEL_e60e3366c42248b797974c752db277b3",
                    "IPY_MODEL_75a95063eaae440c9bff336e7b4f2031"
                ],
                "layout": "IPY_MODEL_e21640ac1aa6407790ae75cf08e162ab"
            }
        },
        "4d50250e66bc462098ffe5b7533b8cb5": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "2014",
                    "2019",
                    "2015",
                    "2018",
                    "2017",
                    "2016",
                    "2012",
                    "2013"
                ],
                "description": "Date : ",
                "index": 1,
                "layout": "IPY_MODEL_48a689b115694e2b8a7ca849a08564b7",
                "style": "IPY_MODEL_eba9cb824e9f4266af5fdf353357c402"
            }
        },
        "4d96df50977c4b5e9cd31aed99e2c65f": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "4da74ad1f4bb459c90fbe7f9ae580754": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "FDIC",
                    "OCC",
                    "SEC",
                    "FHFA",
                    "CFTC"
                ],
                "description": "Regulator :",
                "index": 1,
                "layout": "IPY_MODEL_051ea114b2944a2580f47fde91d8259b",
                "style": "IPY_MODEL_7aa1801f774a4a6bb09b5a41b148d424"
            }
        },
        "4dca70825dea44a1b816e3922f10e36b": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "OCC",
                    "FDIC",
                    "SEC",
                    "FHFA",
                    "CFTC"
                ],
                "description": "Regulator :",
                "index": 0,
                "layout": "IPY_MODEL_8aa6ecbd5624448a8e44eb705e83d065",
                "style": "IPY_MODEL_cafdf0b3916a4d24afbd4aceb8dc4a08"
            }
        },
        "4dfc48662b2f444b9fd0d5631429fffc": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "Alabama",
                    "Arizona",
                    "Arkansas",
                    "California",
                    "Colorado",
                    "Connecticut",
                    "Delaware",
                    "District of Columbia",
                    "Florida",
                    "Georgia",
                    "Hawaii",
                    "Idaho",
                    "Illinois",
                    "Indiana",
                    "Iowa",
                    "Kansas",
                    "Kentucky",
                    "Louisiana",
                    "Maine",
                    "Maryland",
                    "Massachusetts",
                    "Michigan",
                    "Minnesota",
                    "Mississippi",
                    "Missouri",
                    "Montana",
                    "Nebraska",
                    "Nevada",
                    "New Hampshire",
                    "New Jersey",
                    "New Mexico",
                    "New York",
                    "North Carolina",
                    "North Dakota",
                    "Ohio",
                    "Oklahoma",
                    "Oregon",
                    "Pennsylvania",
                    "Puerto Rico",
                    "Rhode Island",
                    "South Carolina",
                    "South Dakota",
                    "Tennessee",
                    "Texas",
                    "Utah",
                    "Vermont",
                    "Virginia",
                    "Washington",
                    "West Virginia",
                    "Wisconsin"
                ],
                "description": "Filing State :",
                "index": 0,
                "layout": "IPY_MODEL_80719ca806014a5b8e6fd09c480aa944",
                "style": "IPY_MODEL_29f1410aa1ac475a8b3ba06595acbfbe"
            }
        },
        "4e3178bca183453e869e559eed7b8b70": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "4e616b3f0f62427e915de85af674cc82": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "4e636f5bfd604211a41306b4ff24fb83": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "4eb907b64c014058bd155e2c1e79bb5d": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "Alabama",
                    "Arizona",
                    "Arkansas",
                    "California",
                    "Colorado",
                    "Connecticut",
                    "Delaware",
                    "District of Columbia",
                    "Florida",
                    "Georgia",
                    "Hawaii",
                    "Idaho",
                    "Illinois",
                    "Indiana",
                    "Iowa",
                    "Kansas",
                    "Kentucky",
                    "Louisiana",
                    "Maine",
                    "Maryland",
                    "Massachusetts",
                    "Michigan",
                    "Minnesota",
                    "Mississippi",
                    "Missouri",
                    "Montana",
                    "Nebraska",
                    "Nevada",
                    "New Hampshire",
                    "New Jersey",
                    "New Mexico",
                    "New York",
                    "North Carolina",
                    "North Dakota",
                    "Ohio",
                    "Oklahoma",
                    "Oregon",
                    "Pennsylvania",
                    "Puerto Rico",
                    "Rhode Island",
                    "South Carolina",
                    "South Dakota",
                    "Tennessee",
                    "Texas",
                    "Utah",
                    "Vermont",
                    "Virginia",
                    "Washington",
                    "West Virginia",
                    "Wisconsin"
                ],
                "description": "Filing State :",
                "index": 0,
                "layout": "IPY_MODEL_032337b9baf349809dce88a4262ca19f",
                "style": "IPY_MODEL_7d0b45053d914ebfb9e6ff4d8fcecb4f"
            }
        },
        "4eeb9b45e09f4e28a23cf8edb9e2c418": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "4f0c6cf02c6947ad9f2115ab9c9c8bad": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "4f4f9b3946ef4343ad7fe5a2dd9d6b1f": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "4f98e24e0c1b4bb5baaabe84212f76f0": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "4fe8aefbdc1747b6b09b363eecc3921e": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "4ffc3ae7e8a24bb1bcd651a9b5fcad59": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "50056a32545b46aaa80eb712e52f31bf": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "501da97b7786431d943044184290df29": {
            "model_name": "FigureModel",
            "model_module": "plotlywidget",
            "model_module_version": "0.9.1",
            "state": {
                "_config": {
                    "plotlyServerURL": "https://plot.ly"
                },
                "_data": [
                    {
                        "hovertext": [
                            "                           Year   Count\nRegulator State                        \nCFTC      New York         2014      84\nFDIC      Alabama          2019     331\n          Arizona          2019     186\n          Arkansas         2019     560\n          California      40331    8778\n          Colorado         2019     712\n          Connecticut      4037     886\n          Delaware        34273   48336\n          Florida         20162    2728\n          Georgia         18149    3055\n          Hawaii           2019     650\n          Idaho            2019     175\n          Illinois        14122    2393\n          Indiana          8074    1344\n          Iowa            14122    1573\n          Kansas           4037     493\n          Kentucky         4037     691\n          Louisiana        8074    2440\n          Maine            2019     577\n          Maryland         8068     561\n          Massachusetts   14122    3640\n          Michigan         4037     476\n          Minnesota        4037     498\n          Mississippi     12107    2325\n          Missouri        16130    1739\n          Montana          2019     324\n          Nebraska        12099    2237\n          Nevada          16131    4792\n          New Hampshire    2019     176\n          New Jersey      14122    2451\n...                         ...     ...\nOCC       Ohio            56448  147585\n          Oklahoma        32255   10561\n          Oregon          34274   10734\n          Pennsylvania    46373   43569\n          Rhode Island    20167    6637\n          South Carolina  18149    9694\n          South Dakota    34282   70376\n          Tennessee       28228   12507\n          Texas           62497  119148\n          Utah            30248   26738\n          Vermont          2019     142\n          Virginia        36288  208722\n          Washington      34274   21786\n          West Virginia   12104    1305\n          Wisconsin       32259    8247\nSEC       Arizona          6047     373\n          California      28235    3240\n          Colorado        14104    1728\n          Connecticut     14122    2093\n          Florida         16135     938\n          Massachusetts   42342    6075\n          Nebraska        26215    2830\n          New Jersey      22178    1663\n          New York        32262    5769\n          Pennsylvania    16130    3075\n          Rhode Island    36297    5476\n          Texas           22187    1428\n          Utah            10076    8051\n          Virginia        14115    1269\n          Washington      16116     966\n\n[117 rows x 2 columns]",
                            "24% market share",
                            "19% market share"
                        ],
                        "orientation": "v",
                        "type": "bar",
                        "uid": "27dac9b8-9e50-4ff3-9883-fe5b4d47db50",
                        "x": [
                            "Credit Card",
                            "Debit Card",
                            "Deposit Account"
                        ],
                        "y": [
                            1045,
                            13804,
                            24168
                        ]
                    }
                ],
                "_js2py_restyle": {},
                "_js2py_update": {},
                "_last_layout_edit_id": 2,
                "_last_trace_edit_id": 1,
                "_layout": {
                    "autosize": true,
                    "barmode": "group",
                    "hovermode": "closest",
                    "template": {},
                    "title": {
                        "text": "SAR Filings by State and Product"
                    },
                    "xaxis": {
                        "title": {
                            "text": "SARs Filing Type"
                        }
                    },
                    "yaxis": {
                        "title": {
                            "text": "Number of Filings"
                        }
                    }
                },
                "_model_module_version": "0.9.1",
                "_py2js_addTraces": {},
                "_py2js_animate": {},
                "_py2js_deleteTraces": {},
                "_py2js_moveTraces": {},
                "_py2js_removeLayoutProps": {},
                "_py2js_removeTraceProps": {},
                "_py2js_restyle": {},
                "_view_count": 0,
                "_view_module_version": "0.9.1"
            }
        },
        "50200d103b7c454db61c678dd257e61f": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "5043f48916ef4627869f6b00df8797f3": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "507387b3fb3242e4b98173e69d26c2ca": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_d42251c5de794ed999c12ec8e5c0ea1f",
                    "IPY_MODEL_4aeed3d15eb747e39c09b2ac0fe9ebc1"
                ],
                "layout": "IPY_MODEL_39a7c41e3395411eb18e2194f09ebe6d"
            }
        },
        "50a972039a324c7ba339eee4768bd67e": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "50bb1b398897457998881254951815fe": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "50e66f1a9d2a4674b976c7f360a12414": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_4c0c98e646964689bd6c577844c6becd",
                    "IPY_MODEL_f930365c5c084daaa47526399074353a"
                ],
                "layout": "IPY_MODEL_d6b8b6da3bfe483f80c200cd558b9032"
            }
        },
        "50e7b8616cd043d3b19474e813e17bd8": {
            "model_name": "VBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_56dd6643a4f3402db46bcd3b5db3bade",
                    "IPY_MODEL_bbbe1a19623f425a904f72dbfadfdf63",
                    "IPY_MODEL_e529e5b8fc684a68b2c4ef9ffb7d7251"
                ],
                "layout": "IPY_MODEL_64ae6f05d58141e6989e21000a3d3172"
            }
        },
        "516358920e5f4c88b9e4307a8f3ca587": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "519f0c1ebba04d05bde3ba66c55975ce": {
            "model_name": "FigureModel",
            "model_module": "plotlywidget",
            "model_module_version": "0.9.1",
            "state": {
                "_config": {
                    "plotlyServerURL": "https://plot.ly"
                },
                "_data": [
                    {
                        "marker": {
                            "color": "rgb(26, 118, 255)",
                            "line": {
                                "color": "rgba(100, 10, 205, 1.0)",
                                "width": 2
                            }
                        },
                        "orientation": "v",
                        "type": "bar",
                        "uid": "ed3e8b7e-a2e7-44af-ab3c-d2f66c1d4113",
                        "x": [
                            "Debit Card",
                            "Deposit Account"
                        ],
                        "y": [
                            223,
                            493
                        ]
                    }
                ],
                "_js2py_pointsCallback": {},
                "_js2py_restyle": {},
                "_js2py_update": {},
                "_last_layout_edit_id": 1,
                "_layout": {
                    "annotations": [
                        {
                            "font": {
                                "color": "red",
                                "size": 10
                            },
                            "showarrow": false,
                            "text": "Source: FINCEN.gov",
                            "x": 1,
                            "xanchor": "right",
                            "xref": "paper",
                            "xshift": 0,
                            "y": -0.15,
                            "yanchor": "auto",
                            "yref": "paper",
                            "yshift": 0
                        }
                    ],
                    "autosize": true,
                    "barmode": "group",
                    "hovermode": "closest",
                    "plot_bgcolor": "brown",
                    "template": {},
                    "title": {
                        "text": "SAR Filings by State and Product"
                    }
                },
                "_model_module_version": "0.9.1",
                "_py2js_addTraces": {},
                "_py2js_animate": {},
                "_py2js_deleteTraces": {},
                "_py2js_moveTraces": {},
                "_py2js_removeLayoutProps": {},
                "_py2js_removeTraceProps": {},
                "_py2js_restyle": {},
                "_py2js_update": {},
                "_view_count": 0,
                "_view_module_version": "0.9.1"
            }
        },
        "51a679bd39b8468d9ff524808ddb3520": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "51def47739ed4c7685e988a21c59e844": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "OCC",
                    "FDIC",
                    "SEC",
                    "FHFA",
                    "CFTC"
                ],
                "description": "Regulator :",
                "index": 0,
                "layout": "IPY_MODEL_0d1d7ebc318b4943a0f7d8c75e9d8f04",
                "style": "IPY_MODEL_27008953cb0243aba94f8cb36534495f"
            }
        },
        "5202ed6e1f7f4e469b8ae4d714068782": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "Alabama",
                    "Arizona",
                    "Arkansas",
                    "California",
                    "Colorado",
                    "Connecticut",
                    "Delaware",
                    "District of Columbia",
                    "Florida",
                    "Georgia",
                    "Hawaii",
                    "Idaho",
                    "Illinois",
                    "Indiana",
                    "Iowa",
                    "Kansas",
                    "Kentucky",
                    "Louisiana",
                    "Maine",
                    "Maryland",
                    "Massachusetts",
                    "Michigan",
                    "Minnesota",
                    "Mississippi",
                    "Missouri",
                    "Montana",
                    "Nebraska",
                    "Nevada",
                    "New Hampshire",
                    "New Jersey",
                    "New Mexico",
                    "New York",
                    "North Carolina",
                    "North Dakota",
                    "Ohio",
                    "Oklahoma",
                    "Oregon",
                    "Pennsylvania",
                    "Puerto Rico",
                    "Rhode Island",
                    "South Carolina",
                    "South Dakota",
                    "Tennessee",
                    "Texas",
                    "Utah",
                    "Vermont",
                    "Virginia",
                    "Washington",
                    "West Virginia",
                    "Wisconsin"
                ],
                "description": "Filing State :",
                "index": 0,
                "layout": "IPY_MODEL_b718fd86d346419780fcfe07f55a4f36",
                "style": "IPY_MODEL_d7a5b3e15f5f4e49a8932194707eb6d1"
            }
        },
        "521a584c44ef4d1aa69e60b33fa9c046": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "2014",
                    "2019",
                    "2015",
                    "2018",
                    "2017",
                    "2016",
                    "2012",
                    "2013"
                ],
                "description": "Date : ",
                "index": 1,
                "layout": "IPY_MODEL_a970ed306b7c49c3bc0e26e1bc576e28",
                "style": "IPY_MODEL_5b2a0c3471e94a3490046f67f6e2e332"
            }
        },
        "52627fd111814cf2b5685482906e05a2": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "Alabama",
                    "Arizona",
                    "Arkansas",
                    "California",
                    "Colorado",
                    "Connecticut",
                    "Delaware",
                    "District of Columbia",
                    "Florida",
                    "Georgia",
                    "Hawaii",
                    "Idaho",
                    "Illinois",
                    "Indiana",
                    "Iowa",
                    "Kansas",
                    "Kentucky",
                    "Louisiana",
                    "Maine",
                    "Maryland",
                    "Massachusetts",
                    "Michigan",
                    "Minnesota",
                    "Mississippi",
                    "Missouri",
                    "Montana",
                    "Nebraska",
                    "Nevada",
                    "New Hampshire",
                    "New Jersey",
                    "New Mexico",
                    "New York",
                    "North Carolina",
                    "North Dakota",
                    "Ohio",
                    "Oklahoma",
                    "Oregon",
                    "Pennsylvania",
                    "Puerto Rico",
                    "Rhode Island",
                    "South Carolina",
                    "South Dakota",
                    "Tennessee",
                    "Texas",
                    "Utah",
                    "Vermont",
                    "Virginia",
                    "Washington",
                    "West Virginia",
                    "Wisconsin"
                ],
                "description": "Filing State :",
                "index": 0,
                "layout": "IPY_MODEL_ccae98e4b26f4e2c8f091fa76e16f40c",
                "style": "IPY_MODEL_2da18d00dc6147678379c083d5da3ca1"
            }
        },
        "52b9680a8ab24668a73284e0063effa1": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "OCC",
                    "FDIC",
                    "SEC",
                    "FHFA",
                    "CFTC"
                ],
                "description": "Regulator :",
                "index": 0,
                "layout": "IPY_MODEL_f55d7cb6eab942cd9bfbc56f54cbc667",
                "style": "IPY_MODEL_20c45df988b04744a2caa5962d593533"
            }
        },
        "52c8086c705f482c8c5ae9687a5d12d3": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "52cfbae5916b46549f5a57d1d86fdb25": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "53030461a936487bbc9b1766b13054a2": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "530a069520054a238c50febf355bccf2": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_1677bf48a0e044678404a6136d9a1082",
                    "IPY_MODEL_ec622642e8b44a2f95cb7d27c348b0ff"
                ],
                "layout": "IPY_MODEL_9669ffa214944d298dc9c88d0b7ec2ac"
            }
        },
        "5349a640dc41425ea6a06332c4930831": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "53b314f6578045ffa7fc65a403d5faf5": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "53b828ad2e1445b3b77341fe8a8b0eba": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_13d890a5a18d4c098081528aa7913786"
                ],
                "layout": "IPY_MODEL_77312068d30847d3a746cb10ae9511cc"
            }
        },
        "542aebaad7204111af810b48979b29d6": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "OCC",
                    "FDIC",
                    "SEC",
                    "FHFA",
                    "CFTC"
                ],
                "description": "Regulator :",
                "index": 0,
                "layout": "IPY_MODEL_849d68ecc58741cab9301e5c4acebcd4",
                "style": "IPY_MODEL_b6abcff35c1645d19d78c186b1ca019c"
            }
        },
        "543a32044fcf497ebe876f1cc14485dc": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "5450c342522b4c96b38139bbbada1a34": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "2014",
                    "2019",
                    "2015",
                    "2018",
                    "2017",
                    "2016",
                    "2012",
                    "2013"
                ],
                "description": "Date : ",
                "index": 1,
                "layout": "IPY_MODEL_290d44860a1a4c2e8b6f3ec9505f9c65",
                "style": "IPY_MODEL_42b770201ee5486db2c0feb654f960e0"
            }
        },
        "5451deda00dd43c3b1251347d9e282cc": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "545d7ae0c4a04f68b1e662fade373ebf": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "546c2b4da66b412a8e3d682818b6f6e5": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "2014",
                    "2019",
                    "2015",
                    "2018",
                    "2017",
                    "2016",
                    "2012",
                    "2013"
                ],
                "description": "Date : ",
                "index": 1,
                "layout": "IPY_MODEL_e8446da8801c48c6a21faf358a6a1cdd",
                "style": "IPY_MODEL_cdb81e0686e943e4ad34c324250646f1"
            }
        },
        "550cada29adf4f289d981fdcee335ff7": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "552dc7cfd9c142169eeef90d9abd9dbd": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_cb05c50d9cf4441faa416c5c5a9f16e0"
                ],
                "layout": "IPY_MODEL_4f0c6cf02c6947ad9f2115ab9c9c8bad"
            }
        },
        "55f18b7976854d2f99d7b630501b329d": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "2014",
                    "2019",
                    "2015",
                    "2018",
                    "2017",
                    "2016",
                    "2012",
                    "2013"
                ],
                "description": "Date : ",
                "index": 1,
                "layout": "IPY_MODEL_20091e7157e24c62876112d00cc2400d",
                "style": "IPY_MODEL_7400e51aea2240eaad38fca1699ca582"
            }
        },
        "5603ee1a991442b29f12dd4427bee223": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "Alabama",
                    "Arizona",
                    "Arkansas",
                    "California",
                    "Colorado",
                    "Connecticut",
                    "Delaware",
                    "District of Columbia",
                    "Florida",
                    "Georgia",
                    "Hawaii",
                    "Idaho",
                    "Illinois",
                    "Indiana",
                    "Iowa",
                    "Kansas",
                    "Kentucky",
                    "Louisiana",
                    "Maine",
                    "Maryland",
                    "Massachusetts",
                    "Michigan",
                    "Minnesota",
                    "Mississippi",
                    "Missouri",
                    "Montana",
                    "Nebraska",
                    "Nevada",
                    "New Hampshire",
                    "New Jersey",
                    "New Mexico",
                    "New York",
                    "North Carolina",
                    "North Dakota",
                    "Ohio",
                    "Oklahoma",
                    "Oregon",
                    "Pennsylvania",
                    "Puerto Rico",
                    "Rhode Island",
                    "South Carolina",
                    "South Dakota",
                    "Tennessee",
                    "Texas",
                    "Utah",
                    "Vermont",
                    "Virginia",
                    "Washington",
                    "West Virginia",
                    "Wisconsin"
                ],
                "description": "Filing State :",
                "index": 3,
                "layout": "IPY_MODEL_ad288b22ecde43dba5be5716f78ddacb",
                "style": "IPY_MODEL_ccce2dc67d3945fa96f5e23015a42087"
            }
        },
        "560a98b9f51b4e38bd76be09caf14290": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "56212a762c354674b1b1aa2934ba2137": {
            "model_name": "VBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_1d28792b3ff448438a7f27aa74236b8e",
                    "IPY_MODEL_624a4b3c8f654a1388da88ddb92f123d",
                    "IPY_MODEL_27aff79243bd4c80978ca400d4a689b0"
                ],
                "layout": "IPY_MODEL_f4e883db17a847039ac556a28970ba5e"
            }
        },
        "56b6c777953b4a8aa6b9eeaa3c3f590c": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "Alabama",
                    "Arizona",
                    "Arkansas",
                    "California",
                    "Colorado",
                    "Connecticut",
                    "Delaware",
                    "District of Columbia",
                    "Florida",
                    "Georgia",
                    "Hawaii",
                    "Idaho",
                    "Illinois",
                    "Indiana",
                    "Iowa",
                    "Kansas",
                    "Kentucky",
                    "Louisiana",
                    "Maine",
                    "Maryland",
                    "Massachusetts",
                    "Michigan",
                    "Minnesota",
                    "Mississippi",
                    "Missouri",
                    "Montana",
                    "Nebraska",
                    "Nevada",
                    "New Hampshire",
                    "New Jersey",
                    "New Mexico",
                    "New York",
                    "North Carolina",
                    "North Dakota",
                    "Ohio",
                    "Oklahoma",
                    "Oregon",
                    "Pennsylvania",
                    "Puerto Rico",
                    "Rhode Island",
                    "South Carolina",
                    "South Dakota",
                    "Tennessee",
                    "Texas",
                    "Utah",
                    "Vermont",
                    "Virginia",
                    "Washington",
                    "West Virginia",
                    "Wisconsin"
                ],
                "description": "Filing State :",
                "index": 0,
                "layout": "IPY_MODEL_dee1e91a869e4428b3f4575010208e50",
                "style": "IPY_MODEL_f7218be0b43447e783988e961c17ee64"
            }
        },
        "56dd6643a4f3402db46bcd3b5db3bade": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_7d05537e9ca341669a8ed3ec98fb7d9a"
                ],
                "layout": "IPY_MODEL_7b25792d334949a091fc85f1e6c28b52"
            }
        },
        "56e77ae1a15d406d83b3d477dce206b4": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "5705d43312e04688807086e1279d5f14": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "OCC",
                    "FDIC",
                    "SEC",
                    "FHFA",
                    "CFTC"
                ],
                "description": "Regulator :",
                "index": 0,
                "layout": "IPY_MODEL_52c8086c705f482c8c5ae9687a5d12d3",
                "style": "IPY_MODEL_7e8e83962de94fa5b41783d7dfcef6d6"
            }
        },
        "577eff3bb01a49bcae8af9fd01c3c3f5": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "579644e5188e4ab2b8d7a6696eb9c03a": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "5810240fbab7452ba672e125d0db04e4": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_b86e4fd124f54a0890ce4f92273cb6b8"
                ],
                "layout": "IPY_MODEL_2e80fda80b98414a9e6282a54a488366"
            }
        },
        "5896c52bca164aa387c23c91871a34b0": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "593718dda83e4600b1e582e6d18792bb": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "59385e63a28a4329910e22bd7a486394": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "Alabama",
                    "Arizona",
                    "Arkansas",
                    "California",
                    "Colorado",
                    "Connecticut",
                    "Delaware",
                    "District of Columbia",
                    "Florida",
                    "Georgia",
                    "Hawaii",
                    "Idaho",
                    "Illinois",
                    "Indiana",
                    "Iowa",
                    "Kansas",
                    "Kentucky",
                    "Louisiana",
                    "Maine",
                    "Maryland",
                    "Massachusetts",
                    "Michigan",
                    "Minnesota",
                    "Mississippi",
                    "Missouri",
                    "Montana",
                    "Nebraska",
                    "Nevada",
                    "New Hampshire",
                    "New Jersey",
                    "New Mexico",
                    "New York",
                    "North Carolina",
                    "North Dakota",
                    "Ohio",
                    "Oklahoma",
                    "Oregon",
                    "Pennsylvania",
                    "Puerto Rico",
                    "Rhode Island",
                    "South Carolina",
                    "South Dakota",
                    "Tennessee",
                    "Texas",
                    "Utah",
                    "Vermont",
                    "Virginia",
                    "Washington",
                    "West Virginia",
                    "Wisconsin"
                ],
                "description": "Filing State :",
                "index": 0,
                "layout": "IPY_MODEL_184c7044f4c440d8b040606cba4e8940",
                "style": "IPY_MODEL_ef99b0dfdb5f4d819be5a33546431fec"
            }
        },
        "5999c0b31d26400d99668dea147b0937": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "59ab32205c1e4dd6966e45d5bcc84bd8": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_f7005da489e645e0ad47f3aa0c18e0f1",
                    "IPY_MODEL_39971ca2602542f9a6829794b9ff07a6"
                ],
                "layout": "IPY_MODEL_42b6dc9d104649f8a05212d47377b16e"
            }
        },
        "59e0e858a233474bb19f000bde63478d": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "OCC",
                    "FDIC",
                    "SEC",
                    "FHFA",
                    "CFTC"
                ],
                "description": "Regulator :",
                "index": 0,
                "layout": "IPY_MODEL_c4fcb204e4b7469698a7bbd450f3a610",
                "style": "IPY_MODEL_7af0576aab5449ac9fd1cf9d2b681055"
            }
        },
        "5a402ecb91054695ba2446f8611b1ee8": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "Alabama",
                    "Arizona",
                    "Arkansas",
                    "California",
                    "Colorado",
                    "Connecticut",
                    "Delaware",
                    "District of Columbia",
                    "Florida",
                    "Georgia",
                    "Hawaii",
                    "Idaho",
                    "Illinois",
                    "Indiana",
                    "Iowa",
                    "Kansas",
                    "Kentucky",
                    "Louisiana",
                    "Maine",
                    "Maryland",
                    "Massachusetts",
                    "Michigan",
                    "Minnesota",
                    "Mississippi",
                    "Missouri",
                    "Montana",
                    "Nebraska",
                    "Nevada",
                    "New Hampshire",
                    "New Jersey",
                    "New Mexico",
                    "New York",
                    "North Carolina",
                    "North Dakota",
                    "Ohio",
                    "Oklahoma",
                    "Oregon",
                    "Pennsylvania",
                    "Puerto Rico",
                    "Rhode Island",
                    "South Carolina",
                    "South Dakota",
                    "Tennessee",
                    "Texas",
                    "Utah",
                    "Vermont",
                    "Virginia",
                    "Washington",
                    "West Virginia",
                    "Wisconsin"
                ],
                "description": "Filing State :",
                "index": 0,
                "layout": "IPY_MODEL_1687645a48ac475ab30cf820eb0063e6",
                "style": "IPY_MODEL_c82087fc12424540b57f304a57677bd0"
            }
        },
        "5a75b1d5fbc74af0986fb6ce9ea5a148": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "5ace3d001e7546849ec15b60a10f65be": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "5afdc52fde0449b1908b4da5a2074ab9": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_7053a7f197a247c694205e6e13e87d60"
                ],
                "layout": "IPY_MODEL_c3084d5339f549799720745c62e6dda4"
            }
        },
        "5b0b1cb3599f4d8e824cf0a922906caf": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "5b0c0124398d471196c6bb14c7d09557": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "5b1bc28d0f054760ae5452ed7d211f19": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "5b2a0c3471e94a3490046f67f6e2e332": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "5b2a7ee6b1a942b384f256282bd98c3a": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "5b2fb93d154043549b746e16b65e5bab": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "5bb5e4da0a954ce894403affdf943c9f": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "5c396b51a18743df8806c160431182b9": {
            "model_name": "FigureModel",
            "model_module": "plotlywidget",
            "model_module_version": "0.9.1",
            "state": {
                "_config": {
                    "plotlyServerURL": "https://plot.ly"
                },
                "_data": [
                    {
                        "orientation": "v",
                        "type": "bar",
                        "uid": "637bab57-ab6f-42f7-925c-03fc9806bb9a",
                        "x": [
                            "Debit Card",
                            "Deposit Account"
                        ],
                        "y": [
                            223,
                            493
                        ]
                    }
                ],
                "_js2py_pointsCallback": {},
                "_js2py_restyle": {},
                "_js2py_update": {},
                "_last_layout_edit_id": 1,
                "_layout": {
                    "annotations": [
                        {
                            "font": {
                                "color": "red",
                                "size": 10
                            },
                            "showarrow": false,
                            "text": "Source: data I found somewhere.",
                            "x": 1,
                            "xanchor": "right",
                            "xref": "paper",
                            "xshift": 0,
                            "y": -0.1,
                            "yanchor": "auto",
                            "yref": "paper",
                            "yshift": 0
                        }
                    ],
                    "autosize": true,
                    "barmode": "group",
                    "hovermode": "closest",
                    "template": {},
                    "title": {
                        "text": "SAR Filings by State and Product"
                    }
                },
                "_model_module_version": "0.9.1",
                "_py2js_addTraces": {},
                "_py2js_animate": {},
                "_py2js_deleteTraces": {},
                "_py2js_moveTraces": {},
                "_py2js_removeLayoutProps": {},
                "_py2js_removeTraceProps": {},
                "_py2js_restyle": {},
                "_py2js_update": {},
                "_view_count": 0,
                "_view_module_version": "0.9.1"
            }
        },
        "5c490978d84b47d7a5732f8d6c76232f": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "5d255c9ae18b4678be6f6822c75fc4b6": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "5d2776331fac440ca2fb61afaba326e0": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_d1e235c69302465ca4e9fd99552b616b"
                ],
                "layout": "IPY_MODEL_a34b768bc770461bb09be42cb3242170"
            }
        },
        "5e2a390c35ca41b3a54c19fde789fd95": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "Alabama",
                    "Arizona",
                    "Arkansas",
                    "California",
                    "Colorado",
                    "Connecticut",
                    "Delaware",
                    "District of Columbia",
                    "Florida",
                    "Georgia",
                    "Hawaii",
                    "Idaho",
                    "Illinois",
                    "Indiana",
                    "Iowa",
                    "Kansas",
                    "Kentucky",
                    "Louisiana",
                    "Maine",
                    "Maryland",
                    "Massachusetts",
                    "Michigan",
                    "Minnesota",
                    "Mississippi",
                    "Missouri",
                    "Montana",
                    "Nebraska",
                    "Nevada",
                    "New Hampshire",
                    "New Jersey",
                    "New Mexico",
                    "New York",
                    "North Carolina",
                    "North Dakota",
                    "Ohio",
                    "Oklahoma",
                    "Oregon",
                    "Pennsylvania",
                    "Puerto Rico",
                    "Rhode Island",
                    "South Carolina",
                    "South Dakota",
                    "Tennessee",
                    "Texas",
                    "Utah",
                    "Vermont",
                    "Virginia",
                    "Washington",
                    "West Virginia",
                    "Wisconsin"
                ],
                "description": "Filing State :",
                "index": 0,
                "layout": "IPY_MODEL_b3f7064867af4ffdb58f66ceb01fe61a",
                "style": "IPY_MODEL_eef75df9c75f400e88d86350c0349532"
            }
        },
        "5e56186875ab4355ae3c155ccc3ce035": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "5e88c8be96214de28173b0827edb80ce": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "5eae50dcd9b24a89b7418a3db031edf5": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "5ec6368b46e844448ba8a5c7731a12c0": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "Alabama",
                    "Arizona",
                    "Arkansas",
                    "California",
                    "Colorado",
                    "Connecticut",
                    "Delaware",
                    "District of Columbia",
                    "Florida",
                    "Georgia",
                    "Hawaii",
                    "Idaho",
                    "Illinois",
                    "Indiana",
                    "Iowa",
                    "Kansas",
                    "Kentucky",
                    "Louisiana",
                    "Maine",
                    "Maryland",
                    "Massachusetts",
                    "Michigan",
                    "Minnesota",
                    "Mississippi",
                    "Missouri",
                    "Montana",
                    "Nebraska",
                    "Nevada",
                    "New Hampshire",
                    "New Jersey",
                    "New Mexico",
                    "New York",
                    "North Carolina",
                    "North Dakota",
                    "Ohio",
                    "Oklahoma",
                    "Oregon",
                    "Pennsylvania",
                    "Puerto Rico",
                    "Rhode Island",
                    "South Carolina",
                    "South Dakota",
                    "Tennessee",
                    "Texas",
                    "Utah",
                    "Vermont",
                    "Virginia",
                    "Washington",
                    "West Virginia",
                    "Wisconsin"
                ],
                "description": "Filing State :",
                "index": 0,
                "layout": "IPY_MODEL_5e56186875ab4355ae3c155ccc3ce035",
                "style": "IPY_MODEL_3c30c87bca7243508196f83858af9147"
            }
        },
        "5ee0773020814c4f9a5000f86157e991": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "5f2c3e5ab0954b0096cfa08814839ef4": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "2014",
                    "2019",
                    "2015",
                    "2018",
                    "2017",
                    "2016",
                    "2012",
                    "2013"
                ],
                "description": "Date : ",
                "index": 1,
                "layout": "IPY_MODEL_69b7e8c845ea4842b982abf139589144",
                "style": "IPY_MODEL_11ec603d78ec4afb8a6fc58504fb839f"
            }
        },
        "5f3a944128a345caae5388d5f6c2174f": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "5f52c040c07443ee88c9a9a79f49a391": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "5f8f4233447c4962b7a836234b648d4b": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "5fdea2bcadc14936b435a5c6b56cad84": {
            "model_name": "FigureModel",
            "model_module": "plotlywidget",
            "model_module_version": "0.9.1",
            "state": {
                "_config": {
                    "plotlyServerURL": "https://plot.ly"
                },
                "_data": [
                    {
                        "orientation": "v",
                        "type": "bar",
                        "uid": "9f7c2bf4-aaba-4263-bac4-c726b909e1dd",
                        "x": [
                            "Debit Card",
                            "Deposit Account"
                        ],
                        "y": [
                            223,
                            493
                        ]
                    }
                ],
                "_js2py_pointsCallback": {},
                "_js2py_restyle": {},
                "_js2py_update": {},
                "_last_layout_edit_id": 1,
                "_layout": {
                    "annotations": [
                        {
                            "font": {
                                "color": "red",
                                "size": 10
                            },
                            "showarrow": false,
                            "text": "Source: data I found somewhere.",
                            "x": 1,
                            "xanchor": "right",
                            "xref": "paper",
                            "xshift": 0,
                            "y": -0.15,
                            "yanchor": "auto",
                            "yref": "paper",
                            "yshift": 0
                        }
                    ],
                    "autosize": true,
                    "barmode": "group",
                    "hovermode": "closest",
                    "template": {},
                    "title": {
                        "text": "SAR Filings by State and Product"
                    }
                },
                "_model_module_version": "0.9.1",
                "_py2js_addTraces": {},
                "_py2js_animate": {},
                "_py2js_deleteTraces": {},
                "_py2js_moveTraces": {},
                "_py2js_removeLayoutProps": {},
                "_py2js_removeTraceProps": {},
                "_py2js_restyle": {},
                "_py2js_update": {},
                "_view_count": 0,
                "_view_module_version": "0.9.1"
            }
        },
        "601cb82ad9bc4f97b8aff62ced7a854f": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "6041ea7cfa7946a386a7a6a50ef87a16": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "605cbf4ea03d4c3b870572c27029c744": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "6092d7bb441a4504a4408eb6a18e9fa1": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "60a3f25018294f44ac8a3c541892f04d": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "2014",
                    "2019",
                    "2015",
                    "2018",
                    "2017",
                    "2016",
                    "2012",
                    "2013"
                ],
                "description": "Date : ",
                "index": 1,
                "layout": "IPY_MODEL_c5db09dac31046be8d51b6db49fd2525",
                "style": "IPY_MODEL_605cbf4ea03d4c3b870572c27029c744"
            }
        },
        "60f4de76251845bbb1e17bea5308cff9": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_88f975a4e9a84226af9d93509b791abc",
                    "IPY_MODEL_51def47739ed4c7685e988a21c59e844"
                ],
                "layout": "IPY_MODEL_ddf323cde11f40e7bdd2940abecdc32d"
            }
        },
        "61430fbbc8a64a4a97701f3d398c4fff": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_33757f176cff48a39222bd4672091c97"
                ],
                "layout": "IPY_MODEL_fc18a5598118445a8b2f671cc1f9da9b"
            }
        },
        "618f0bdcec134ec2b27b169a101d82f8": {
            "model_name": "VBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_a6868e0f72b34bc9859b8a287e7dc27f",
                    "IPY_MODEL_b73f1ce3ff4e4b94b479541873c906e2",
                    "IPY_MODEL_df3ea7308b134c34a5749656f1bad0f8"
                ],
                "layout": "IPY_MODEL_6eff999e0e974d9e98a9a5b9ed7f116d"
            }
        },
        "624a4b3c8f654a1388da88ddb92f123d": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_21d1d087eec64dd7bdb6e44d0fcbf627",
                    "IPY_MODEL_8aa70ccf2039482c9b3ba267cf3c01ea"
                ],
                "layout": "IPY_MODEL_43d70abf655f4a808f971be63189afdd"
            }
        },
        "625b5bce455842d6b971c0650edd6819": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_ad1d127b106143dfa18a48f792a30411",
                    "IPY_MODEL_dcc6e625b13e44029fe1f2816bed0203"
                ],
                "layout": "IPY_MODEL_3de450af77744ffe95db0cbd8c7c1295"
            }
        },
        "627da2c7c79d42219c6c472548030643": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "629caff267bc40e48a0ba4a269524c4d": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "Alabama",
                    "Arizona",
                    "Arkansas",
                    "California",
                    "Colorado",
                    "Connecticut",
                    "Delaware",
                    "District of Columbia",
                    "Florida",
                    "Georgia",
                    "Hawaii",
                    "Idaho",
                    "Illinois",
                    "Indiana",
                    "Iowa",
                    "Kansas",
                    "Kentucky",
                    "Louisiana",
                    "Maine",
                    "Maryland",
                    "Massachusetts",
                    "Michigan",
                    "Minnesota",
                    "Mississippi",
                    "Missouri",
                    "Montana",
                    "Nebraska",
                    "Nevada",
                    "New Hampshire",
                    "New Jersey",
                    "New Mexico",
                    "New York",
                    "North Carolina",
                    "North Dakota",
                    "Ohio",
                    "Oklahoma",
                    "Oregon",
                    "Pennsylvania",
                    "Puerto Rico",
                    "Rhode Island",
                    "South Carolina",
                    "South Dakota",
                    "Tennessee",
                    "Texas",
                    "Utah",
                    "Vermont",
                    "Virginia",
                    "Washington",
                    "West Virginia",
                    "Wisconsin"
                ],
                "description": "Filing State :",
                "index": 0,
                "layout": "IPY_MODEL_4579647012c64433891268ed654bd5df",
                "style": "IPY_MODEL_db61029692fd4b76aec82419ce012216"
            }
        },
        "62da565d88414f1d941160c438429bfa": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "62fea995ba5a40bfb858a7208ab89f60": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "OCC",
                    "FDIC",
                    "SEC",
                    "FHFA",
                    "CFTC"
                ],
                "description": "Regulator :",
                "index": 0,
                "layout": "IPY_MODEL_3f150c57b53c4da5b4b06337c1db033f",
                "style": "IPY_MODEL_72b58205cfb749feb71a63468d7b5c6a"
            }
        },
        "631406d68761445bb4d28417718ad106": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "63f5c49c67354e10a3e66b5008456913": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "64075ff0953f40bc9d05eb1569116850": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "644009bd949249c089175d25d01f9d21": {
            "model_name": "FigureModel",
            "model_module": "plotlywidget",
            "model_module_version": "0.9.1",
            "state": {
                "_config": {
                    "plotlyServerURL": "https://plot.ly"
                },
                "_data": [
                    {
                        "marker": {
                            "color": "rgb(26, 118, 255)",
                            "line": {
                                "color": "rgba(100, 10, 205, 1.0)",
                                "width": 2
                            }
                        },
                        "orientation": "v",
                        "type": "bar",
                        "uid": "ea83b188-f6a9-40f1-800d-113193e6962a",
                        "x": [
                            "Debit Card",
                            "Deposit Account"
                        ],
                        "y": [
                            223,
                            493
                        ]
                    }
                ],
                "_js2py_pointsCallback": {},
                "_js2py_restyle": {},
                "_js2py_update": {},
                "_last_layout_edit_id": 1,
                "_layout": {
                    "annotations": [
                        {
                            "font": {
                                "color": "red",
                                "size": 10
                            },
                            "showarrow": false,
                            "text": "Source: FINCEN.gov",
                            "x": 1,
                            "xanchor": "right",
                            "xref": "paper",
                            "xshift": 0,
                            "y": -0.15,
                            "yanchor": "auto",
                            "yref": "paper",
                            "yshift": 0
                        }
                    ],
                    "autosize": true,
                    "barmode": "group",
                    "hovermode": "closest",
                    "plot_bgcolor": "light grey",
                    "template": {},
                    "title": {
                        "text": "SAR Filings by State and Product"
                    }
                },
                "_model_module_version": "0.9.1",
                "_py2js_addTraces": {},
                "_py2js_animate": {},
                "_py2js_deleteTraces": {},
                "_py2js_moveTraces": {},
                "_py2js_removeLayoutProps": {},
                "_py2js_removeTraceProps": {},
                "_py2js_restyle": {},
                "_py2js_update": {},
                "_view_count": 0,
                "_view_module_version": "0.9.1"
            }
        },
        "645f7636b383427bb244b6d978215a8e": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "646cea3bafa64cb78f6e41f2c35bfc2a": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "64ae6f05d58141e6989e21000a3d3172": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "64c2e8c8af224241ade088d157e676cf": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_b696cb325e8f4becb59f2100f3ca5ccf"
                ],
                "layout": "IPY_MODEL_69518c9fd10d4232a14771215c77173f"
            }
        },
        "64dbf1542fe246e79b16f0abb7f41847": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "655c431ffb304e048a9185305018fe40": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "657a16c8a9f347dd9f3bb8ad374ec969": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "OCC",
                    "FDIC",
                    "SEC",
                    "FHFA",
                    "CFTC"
                ],
                "description": "Regulator :",
                "index": 0,
                "layout": "IPY_MODEL_e49190719ae3415a9e68e210cc72b34e",
                "style": "IPY_MODEL_700bfb690865421392dfc9a905d0a1ee"
            }
        },
        "6592e785c51f489292b806b48f524d3c": {
            "model_name": "VBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_0ac126afbc16447fb6bd64d22e241157",
                    "IPY_MODEL_cce55c15785d4b069e2190eeb45c4e54",
                    "IPY_MODEL_857eab6713ca4af085589d0964b7ce00"
                ],
                "layout": "IPY_MODEL_70faff8c62284750942a8f9685cefd35"
            }
        },
        "65cbc0e278f64be2a9d2e4756597e607": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "66521a7ae6774f2baba377d24867ff80": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_3abd5898c1b34824bb2fac6383283afa"
                ],
                "layout": "IPY_MODEL_5b2a7ee6b1a942b384f256282bd98c3a"
            }
        },
        "66850175307c487f90ca464d951b5ad4": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "6686a700a6e34fd39f973c5a9ceb0117": {
            "model_name": "FigureModel",
            "model_module": "plotlywidget",
            "model_module_version": "0.9.1",
            "state": {
                "_config": {
                    "plotlyServerURL": "https://plot.ly"
                },
                "_data": [
                    {
                        "orientation": "v",
                        "type": "bar",
                        "uid": "1f643387-af21-49ab-ad0e-6bf6a0008720",
                        "x": [
                            "Debit Card",
                            "Deposit Account"
                        ],
                        "y": [
                            223,
                            493
                        ]
                    }
                ],
                "_js2py_pointsCallback": {},
                "_js2py_restyle": {},
                "_js2py_update": {},
                "_last_layout_edit_id": 1,
                "_layout": {
                    "autosize": true,
                    "barmode": "group",
                    "hovermode": "closest",
                    "template": {},
                    "title": {
                        "text": "SAR Filings by State and Product"
                    }
                },
                "_model_module_version": "0.9.1",
                "_py2js_addTraces": {},
                "_py2js_animate": {},
                "_py2js_deleteTraces": {},
                "_py2js_moveTraces": {},
                "_py2js_removeLayoutProps": {},
                "_py2js_removeTraceProps": {},
                "_py2js_restyle": {},
                "_py2js_update": {},
                "_view_count": 0,
                "_view_module_version": "0.9.1"
            }
        },
        "66c4f1440f8e4f8d8b4da22964a3dc51": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "66cfa7970fff4284960914b52d3cafc5": {
            "model_name": "VBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_36de34e1dac14d6bb452cf6daeb725a0",
                    "IPY_MODEL_942de696def14024bf8d0e52c98d694b",
                    "IPY_MODEL_6cef2703bfc54cb69ceed4e0bff602f7"
                ],
                "layout": "IPY_MODEL_6f1218354aa243d8a584ad3b34915499"
            }
        },
        "66f3148ce1854a9abad8ca1abd976130": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "6720438d3f514a198be600412fc70395": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "6759232517e04689b9ed527b0cfaa408": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_2ace85f85b8646d0950a4fc5e0ee6f1c"
                ],
                "layout": "IPY_MODEL_e87389e598c747f9a1b6bc07370d44b4"
            }
        },
        "6784d99804724d2b953e5eebcf85f050": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "67868449c24d46fc87af7eb699809576": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "67aa5716479f4b88837586a5edbf025a": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_36bf0002b54f490a9678dca70636ab76",
                    "IPY_MODEL_5705d43312e04688807086e1279d5f14"
                ],
                "layout": "IPY_MODEL_9c0c5cb345134cadbe267b5fec4d8221"
            }
        },
        "67bfefedd2614b2ca931a08e28007cc8": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "67f42c2c4503455caca77ddb1c5aa138": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "67f994923765424e903d1793be35c9b7": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "67fbb5690ea84d6b868df2124a3d6007": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "686b7a29961443ea83136f1d425a3a57": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "Alabama",
                    "Arizona",
                    "Arkansas",
                    "California",
                    "Colorado",
                    "Connecticut",
                    "Delaware",
                    "District of Columbia",
                    "Florida",
                    "Georgia",
                    "Hawaii",
                    "Idaho",
                    "Illinois",
                    "Indiana",
                    "Iowa",
                    "Kansas",
                    "Kentucky",
                    "Louisiana",
                    "Maine",
                    "Maryland",
                    "Massachusetts",
                    "Michigan",
                    "Minnesota",
                    "Mississippi",
                    "Missouri",
                    "Montana",
                    "Nebraska",
                    "Nevada",
                    "New Hampshire",
                    "New Jersey",
                    "New Mexico",
                    "New York",
                    "North Carolina",
                    "North Dakota",
                    "Ohio",
                    "Oklahoma",
                    "Oregon",
                    "Pennsylvania",
                    "Puerto Rico",
                    "Rhode Island",
                    "South Carolina",
                    "South Dakota",
                    "Tennessee",
                    "Texas",
                    "Utah",
                    "Vermont",
                    "Virginia",
                    "Washington",
                    "West Virginia",
                    "Wisconsin"
                ],
                "description": "Filing State :",
                "index": 0,
                "layout": "IPY_MODEL_fd575400b9a945328719b5309a2d75a7",
                "style": "IPY_MODEL_bdbc6ff5ea2b4091925d72c367a470b3"
            }
        },
        "688521878d414a3e9e3e81b1e0402ec7": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "OCC",
                    "FDIC",
                    "SEC",
                    "FHFA",
                    "CFTC"
                ],
                "description": "Regulator :",
                "index": 0,
                "layout": "IPY_MODEL_601cb82ad9bc4f97b8aff62ced7a854f",
                "style": "IPY_MODEL_f4949ef841f94753b62b45e0cb3c1eab"
            }
        },
        "68b33582cef142a4bbfd5b0cb266a9b7": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "Alabama",
                    "Arizona",
                    "Arkansas",
                    "California",
                    "Colorado",
                    "Connecticut",
                    "Delaware",
                    "District of Columbia",
                    "Florida",
                    "Georgia",
                    "Hawaii",
                    "Idaho",
                    "Illinois",
                    "Indiana",
                    "Iowa",
                    "Kansas",
                    "Kentucky",
                    "Louisiana",
                    "Maine",
                    "Maryland",
                    "Massachusetts",
                    "Michigan",
                    "Minnesota",
                    "Mississippi",
                    "Missouri",
                    "Montana",
                    "Nebraska",
                    "Nevada",
                    "New Hampshire",
                    "New Jersey",
                    "New Mexico",
                    "New York",
                    "North Carolina",
                    "North Dakota",
                    "Ohio",
                    "Oklahoma",
                    "Oregon",
                    "Pennsylvania",
                    "Puerto Rico",
                    "Rhode Island",
                    "South Carolina",
                    "South Dakota",
                    "Tennessee",
                    "Texas",
                    "Utah",
                    "Vermont",
                    "Virginia",
                    "Washington",
                    "West Virginia",
                    "Wisconsin"
                ],
                "description": "Filing State :",
                "index": 0,
                "layout": "IPY_MODEL_88a220c6b9c54dc2a74d4637d0e971d1",
                "style": "IPY_MODEL_6ee4bcd5355648e3ae5491074ecf0754"
            }
        },
        "68e3de60ae0d400db88062a58e7c2b28": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "69518c9fd10d4232a14771215c77173f": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "695f07c49bb64140886e60ea494b3738": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "6963eeacc71e4e7c90f5b67163c6431c": {
            "model_name": "VBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_34daa25565014c5a933824d0c536d38e",
                    "IPY_MODEL_d37e8eb56ce1417b931a0717764eacba",
                    "IPY_MODEL_dfd7a686ceb645178c64c5d6cc91a3d7"
                ],
                "layout": "IPY_MODEL_c25d936d9d674f33ae44cce907b07f49"
            }
        },
        "698d0fc8fa2a45bdb67ed35a221874d7": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "69b7e8c845ea4842b982abf139589144": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "69d77fee427a42cd82efad2f817f76ae": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "6a9ae312b2ab4c51a2db082f05086867": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "6abb99e4099249389f4d5f46d1c9de73": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "6ad755a6f0674c43900c6123c39df0ac": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "OCC",
                    "FDIC",
                    "SEC",
                    "FHFA",
                    "CFTC"
                ],
                "description": "Regulator :",
                "index": 0,
                "layout": "IPY_MODEL_897c7dc3e5324026bcbc03a237a90108",
                "style": "IPY_MODEL_bac43357dd3d4d0eb041a18588d30bad"
            }
        },
        "6b1adc502fa544708a82e5675e6c8ca3": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "6b5f765d111c45c596f86defb17a687c": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_f857d742aa334822b3a0318cf4de3bea"
                ],
                "layout": "IPY_MODEL_5a75b1d5fbc74af0986fb6ce9ea5a148"
            }
        },
        "6b6bd2ad130e4cebbf1b4bba66c54913": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "6b6ca495c5e8406db2f0641b79eaa93a": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "OCC",
                    "FDIC",
                    "SEC",
                    "FHFA",
                    "CFTC"
                ],
                "description": "Regulator :",
                "index": 0,
                "layout": "IPY_MODEL_36a764f9e2bf4485bc2df21f747bdeae",
                "style": "IPY_MODEL_b51fe10f6cc344ffad709c0ae0569d06"
            }
        },
        "6bbc773a0f034f7a9a6e2b6f2c38fb1a": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "6be37819229c4a2ea5c48409c7e7bec2": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "OCC",
                    "FDIC",
                    "SEC",
                    "FHFA",
                    "CFTC"
                ],
                "description": "Regulator :",
                "index": 0,
                "layout": "IPY_MODEL_5b0c0124398d471196c6bb14c7d09557",
                "style": "IPY_MODEL_ea415e3debcf4c039f7ed46e60cd0850"
            }
        },
        "6ccbec0fea88445b901d6cfc273511e5": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "6ce864fe5f21471c9cb6ddc675a18151": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_4d50250e66bc462098ffe5b7533b8cb5"
                ],
                "layout": "IPY_MODEL_39cd31d0bc5c447c8b3a27187e827a18"
            }
        },
        "6cef2703bfc54cb69ceed4e0bff602f7": {
            "model_name": "FigureModel",
            "model_module": "plotlywidget",
            "model_module_version": "0.9.1",
            "state": {
                "_config": {
                    "plotlyServerURL": "https://plot.ly"
                },
                "_data": [
                    {
                        "marker": {
                            "color": "rgb(26, 118, 255)",
                            "line": {
                                "color": "rgba(100, 10, 205, 1.0)",
                                "width": 2
                            }
                        },
                        "orientation": "v",
                        "type": "bar",
                        "uid": "38f0c437-9492-4cc7-9eab-ba08cb9926d1",
                        "x": [
                            "Debit Card",
                            "Deposit Account"
                        ],
                        "y": [
                            223,
                            493
                        ]
                    }
                ],
                "_js2py_pointsCallback": {},
                "_js2py_restyle": {},
                "_js2py_update": {},
                "_last_layout_edit_id": 1,
                "_layout": {
                    "annotations": [
                        {
                            "font": {
                                "color": "red",
                                "size": 10
                            },
                            "showarrow": false,
                            "text": "Source: FINCEN.gov",
                            "x": 1,
                            "xanchor": "right",
                            "xref": "paper",
                            "xshift": 0,
                            "y": -0.15,
                            "yanchor": "auto",
                            "yref": "paper",
                            "yshift": 0
                        }
                    ],
                    "autosize": true,
                    "barmode": "group",
                    "hovermode": "closest",
                    "paper_bgcolor": "whitesmoke",
                    "plot_bgcolor": "whitesmoke",
                    "shapes": [
                        {
                            "line": {
                                "color": "RoyalBlue"
                            },
                            "type": "rect",
                            "x0": 0,
                            "x1": 0,
                            "y0": 0,
                            "y1": 0
                        }
                    ],
                    "template": {},
                    "title": {
                        "text": "Number SAR Filings by State and Product\n(Greater than 80)"
                    }
                },
                "_model_module_version": "0.9.1",
                "_py2js_addTraces": {},
                "_py2js_animate": {},
                "_py2js_deleteTraces": {},
                "_py2js_moveTraces": {},
                "_py2js_removeLayoutProps": {},
                "_py2js_removeTraceProps": {},
                "_py2js_restyle": {},
                "_py2js_update": {},
                "_view_count": 0,
                "_view_module_version": "0.9.1"
            }
        },
        "6d08548253e54652962318fd87e0bfe1": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "6d40efcebadf4164a8a2ff14ce8064f1": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "OCC",
                    "FDIC",
                    "SEC",
                    "FHFA",
                    "CFTC"
                ],
                "description": "Regulator :",
                "index": 0,
                "layout": "IPY_MODEL_11f91d4e059647b393cb1880c33f1ef6",
                "style": "IPY_MODEL_f5dcc0b6041046c5b77bc7cd131e4a1e"
            }
        },
        "6d864cc0141649e884700bd5292cde90": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "OCC",
                    "FDIC",
                    "SEC",
                    "FHFA",
                    "CFTC"
                ],
                "description": "Regulator :",
                "index": 0,
                "layout": "IPY_MODEL_31e32b8b94be4d3498890e7532e0c217",
                "style": "IPY_MODEL_032c9ef3ad6748109af8c122bea84998"
            }
        },
        "6d9581a36b2743b79a7f805137f810d4": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "6da243f63b5e46b691c91d65fc2fd0fa": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "6dc0aee9e34c4d41ab23fd4cf5f3a798": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "6dc3b32ec0be4898a79b76d36edd1179": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "Alabama",
                    "Arizona",
                    "Arkansas",
                    "California",
                    "Colorado",
                    "Connecticut",
                    "Delaware",
                    "District of Columbia",
                    "Florida",
                    "Georgia",
                    "Hawaii",
                    "Idaho",
                    "Illinois",
                    "Indiana",
                    "Iowa",
                    "Kansas",
                    "Kentucky",
                    "Louisiana",
                    "Maine",
                    "Maryland",
                    "Massachusetts",
                    "Michigan",
                    "Minnesota",
                    "Mississippi",
                    "Missouri",
                    "Montana",
                    "Nebraska",
                    "Nevada",
                    "New Hampshire",
                    "New Jersey",
                    "New Mexico",
                    "New York",
                    "North Carolina",
                    "North Dakota",
                    "Ohio",
                    "Oklahoma",
                    "Oregon",
                    "Pennsylvania",
                    "Puerto Rico",
                    "Rhode Island",
                    "South Carolina",
                    "South Dakota",
                    "Tennessee",
                    "Texas",
                    "Utah",
                    "Vermont",
                    "Virginia",
                    "Washington",
                    "West Virginia",
                    "Wisconsin"
                ],
                "description": "Filing State :",
                "index": 0,
                "layout": "IPY_MODEL_6abb99e4099249389f4d5f46d1c9de73",
                "style": "IPY_MODEL_dab316a998c041ed83d9e10b735e1a44"
            }
        },
        "6dd2aca5cf1a414b800dc1d19eb03e7a": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "OCC",
                    "FDIC",
                    "SEC",
                    "FHFA",
                    "CFTC"
                ],
                "description": "Regulator :",
                "index": 0,
                "layout": "IPY_MODEL_c9fdee2009a443cc9b72511ee98fd1da",
                "style": "IPY_MODEL_e4a3b6c88de44b5d9efd621aefb35a05"
            }
        },
        "6de33d948e6f41f09d1399121faeefba": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "OCC",
                    "FDIC",
                    "SEC",
                    "FHFA",
                    "CFTC"
                ],
                "description": "Regulator :",
                "index": 0,
                "layout": "IPY_MODEL_eb68cddcce224abf8fe5c0a55f43d42c",
                "style": "IPY_MODEL_07729b2cc35c477bbda2631d40709767"
            }
        },
        "6e20abc433a04260ac246ca8087b975a": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "6e218126c2a6499e854aa07b9ef9fbb2": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "6e697ac8847347eaaa6ca4c9060539af": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "OCC",
                    "FDIC",
                    "SEC",
                    "FHFA",
                    "CFTC"
                ],
                "description": "Regulator :",
                "index": 0,
                "layout": "IPY_MODEL_113ce5f7e51e450096855924e592b467",
                "style": "IPY_MODEL_f37de8ee492d4975961cce86b991ce53"
            }
        },
        "6e69c07747cb41de88b0525cbead06af": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "OCC",
                    "FDIC",
                    "SEC",
                    "FHFA",
                    "CFTC"
                ],
                "description": "Regulator :",
                "index": 0,
                "layout": "IPY_MODEL_c7a2507b63134c05a92c22df5af1bb55",
                "style": "IPY_MODEL_6b6bd2ad130e4cebbf1b4bba66c54913"
            }
        },
        "6e94c722dcb644dd8702dff06ef5475e": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_ef9f573e259f41009a6b08cccd71babc"
                ],
                "layout": "IPY_MODEL_3806290d829749ef90600b5596851b2e"
            }
        },
        "6ee4bcd5355648e3ae5491074ecf0754": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "6eff999e0e974d9e98a9a5b9ed7f116d": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "6f1218354aa243d8a584ad3b34915499": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "6f33e73b89914c38917eb867cf03721a": {
            "model_name": "VBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_3bbc07357a3c4e739d9ffa2953109c1a",
                    "IPY_MODEL_67aa5716479f4b88837586a5edbf025a",
                    "IPY_MODEL_3fa3f2257eb9448d8144db1ffc871540"
                ],
                "layout": "IPY_MODEL_66c4f1440f8e4f8d8b4da22964a3dc51"
            }
        },
        "6f6a47b4db504e989a4b4a7c48229b6b": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "6fb39882844444cca60254f74b3d65f7": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "6ffc37314b2841d2b2d27c9712813143": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "700bfb690865421392dfc9a905d0a1ee": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "70158a6e99b440beaf0e5b808d120ff3": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_9d533c674e19409ba0afc87a4bb368d5",
                    "IPY_MODEL_a40b4173d4c7429ea699f45ff19e4baa"
                ],
                "layout": "IPY_MODEL_6fb39882844444cca60254f74b3d65f7"
            }
        },
        "70362de47508439e98f2ab01cea6702d": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_bdbb1db9b54345e0b4528e79b20f8a09",
                    "IPY_MODEL_29031f2aedd14b17af0e7f47e6404691"
                ],
                "layout": "IPY_MODEL_a3c732551ca54891a52443d98d7990e0"
            }
        },
        "7053a7f197a247c694205e6e13e87d60": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "2014",
                    "2019",
                    "2015",
                    "2018",
                    "2017",
                    "2016",
                    "2012",
                    "2013"
                ],
                "description": "Date : ",
                "index": 1,
                "layout": "IPY_MODEL_ab326676bfee40aba5bbef345929f3bf",
                "style": "IPY_MODEL_07be55243fdf46b4870fc72e90d8c8fc"
            }
        },
        "705a69602939428a9f1e0cea16fb165a": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "7061cc2d40a74efa90a825adefd5b54c": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "Alabama",
                    "Arizona",
                    "Arkansas",
                    "California",
                    "Colorado",
                    "Connecticut",
                    "Delaware",
                    "District of Columbia",
                    "Florida",
                    "Georgia",
                    "Hawaii",
                    "Idaho",
                    "Illinois",
                    "Indiana",
                    "Iowa",
                    "Kansas",
                    "Kentucky",
                    "Louisiana",
                    "Maine",
                    "Maryland",
                    "Massachusetts",
                    "Michigan",
                    "Minnesota",
                    "Mississippi",
                    "Missouri",
                    "Montana",
                    "Nebraska",
                    "Nevada",
                    "New Hampshire",
                    "New Jersey",
                    "New Mexico",
                    "New York",
                    "North Carolina",
                    "North Dakota",
                    "Ohio",
                    "Oklahoma",
                    "Oregon",
                    "Pennsylvania",
                    "Puerto Rico",
                    "Rhode Island",
                    "South Carolina",
                    "South Dakota",
                    "Tennessee",
                    "Texas",
                    "Utah",
                    "Vermont",
                    "Virginia",
                    "Washington",
                    "West Virginia",
                    "Wisconsin"
                ],
                "description": "Filing State :",
                "index": 0,
                "layout": "IPY_MODEL_cc240ba5d48646eeb2066a52d5fe4585",
                "style": "IPY_MODEL_f55f4c74bfa3461fa464b8bcf451669a"
            }
        },
        "70dc74955c4242d2aed7511285be3b07": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "OCC",
                    "FDIC",
                    "SEC",
                    "FHFA",
                    "CFTC"
                ],
                "description": "Regulator :",
                "index": 0,
                "layout": "IPY_MODEL_f19697e076b249909776b97ce59e7b9e",
                "style": "IPY_MODEL_a581144434934f3fa01d830747f9a037"
            }
        },
        "70e1a35a3188493a83fa09e59e3d8dec": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "70e4ecada8cb48a1a985300413dc8fe8": {
            "model_name": "FigureModel",
            "model_module": "plotlywidget",
            "model_module_version": "0.9.1",
            "state": {
                "_config": {
                    "plotlyServerURL": "https://plot.ly"
                },
                "_data": [
                    {
                        "orientation": "v",
                        "type": "bar",
                        "uid": "871bad6e-aaec-44b9-9be1-6c22aee871cc",
                        "x": [
                            "Debit Card",
                            "Deposit Account"
                        ],
                        "y": [
                            223,
                            493
                        ]
                    }
                ],
                "_js2py_pointsCallback": {},
                "_js2py_restyle": {},
                "_js2py_update": {},
                "_last_layout_edit_id": 1,
                "_layout": {
                    "annotations": [
                        {
                            "font": {
                                "color": "red",
                                "size": 15
                            },
                            "showarrow": false,
                            "text": "Source: data I found somewhere.",
                            "x": 1,
                            "xanchor": "right",
                            "xref": "paper",
                            "xshift": 0,
                            "y": -0.1,
                            "yanchor": "auto",
                            "yref": "paper",
                            "yshift": 0
                        }
                    ],
                    "autosize": true,
                    "barmode": "group",
                    "hovermode": "closest",
                    "template": {},
                    "title": {
                        "text": "SAR Filings by State and Product"
                    }
                },
                "_model_module_version": "0.9.1",
                "_py2js_addTraces": {},
                "_py2js_animate": {},
                "_py2js_deleteTraces": {},
                "_py2js_moveTraces": {},
                "_py2js_removeLayoutProps": {},
                "_py2js_removeTraceProps": {},
                "_py2js_restyle": {},
                "_py2js_update": {},
                "_view_count": 0,
                "_view_module_version": "0.9.1"
            }
        },
        "70e9bd2e051740179e016159db6032f7": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "70faff8c62284750942a8f9685cefd35": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "714479d5009740a19b4bd68b3c11376e": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "Alabama",
                    "Arizona",
                    "Arkansas",
                    "California",
                    "Colorado",
                    "Connecticut",
                    "Delaware",
                    "District of Columbia",
                    "Florida",
                    "Georgia",
                    "Hawaii",
                    "Idaho",
                    "Illinois",
                    "Indiana",
                    "Iowa",
                    "Kansas",
                    "Kentucky",
                    "Louisiana",
                    "Maine",
                    "Maryland",
                    "Massachusetts",
                    "Michigan",
                    "Minnesota",
                    "Mississippi",
                    "Missouri",
                    "Montana",
                    "Nebraska",
                    "Nevada",
                    "New Hampshire",
                    "New Jersey",
                    "New Mexico",
                    "New York",
                    "North Carolina",
                    "North Dakota",
                    "Ohio",
                    "Oklahoma",
                    "Oregon",
                    "Pennsylvania",
                    "Puerto Rico",
                    "Rhode Island",
                    "South Carolina",
                    "South Dakota",
                    "Tennessee",
                    "Texas",
                    "Utah",
                    "Vermont",
                    "Virginia",
                    "Washington",
                    "West Virginia",
                    "Wisconsin"
                ],
                "description": "Filing State :",
                "index": 0,
                "layout": "IPY_MODEL_fb4ffc46eee345c2b931fd99e62a9d0d",
                "style": "IPY_MODEL_ece35dcac6904ca894c81b4d6e6659b8"
            }
        },
        "715f90a2d7f145ebb8f41b05788c0e5b": {
            "model_name": "VBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_8eb5290419fc4763a656ff42004891ff",
                    "IPY_MODEL_8ffd5779ca134fd1bdee87b3854ce6af",
                    "IPY_MODEL_ae760c3dc5b7415b9bb5ae254adf6a59"
                ],
                "layout": "IPY_MODEL_51a679bd39b8468d9ff524808ddb3520"
            }
        },
        "71b5fe6863fb4d02b81c099c238ebcdb": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "71d3462869a44136a22f1bf434a38867": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "71d5f258ec574c87a4a32078a56a6d82": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "72b58205cfb749feb71a63468d7b5c6a": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "72ce4bd63f104f2697fc53f642a242e0": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "72e754996ebc4fcfa6db9009c606391f": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "732cf2e9a9b04f8b89b56e5fb737df9b": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_c934f157dc6f405da141ec5109345ff0"
                ],
                "layout": "IPY_MODEL_91ac0dac4e234e0897b1197eef744a8d"
            }
        },
        "737fcc07a0184a71b4c3fd1d1d4a1a52": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "2014",
                    "2019",
                    "2015",
                    "2018",
                    "2017",
                    "2016",
                    "2012",
                    "2013"
                ],
                "description": "Date : ",
                "index": 1,
                "layout": "IPY_MODEL_3731e648613e482590ccc0934d0f75bb",
                "style": "IPY_MODEL_2091be7a5b914414b6187120fecf8566"
            }
        },
        "73c0ae5e7a514490ac9ea670cd48445a": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "73df7fbe0c1d4c5b88236fe55d8a5275": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "7400e51aea2240eaad38fca1699ca582": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "7418b603306d49e385e4eb4d39ed1034": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "743dfc534dbc49e7940e5bb1409325fc": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_1357cc7b545644efb89e0a8c1b099a45",
                    "IPY_MODEL_1b74d5410f4c49c1b7c0c03027c2e55c"
                ],
                "layout": "IPY_MODEL_787d94225a864857a4a59552b64731bf"
            }
        },
        "746b966b3ffe43c096367726e0a9f9f5": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_f4454819a3fa4d60a5a5c8e37e08917b"
                ],
                "layout": "IPY_MODEL_4a76acbef54f4fed97d4e39693a8cf6b"
            }
        },
        "74a10d911cc045adb5deb5006747190a": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_8ef4fb5ae7c547428869a904bd0989d8"
                ],
                "layout": "IPY_MODEL_9c711bd95d714b1c9103262bd9b6c1cc"
            }
        },
        "74ae3ce45b544b558624da06216a949a": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "74cd2f706d49426ab34db595db04415b": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "74d4c7c110ae451a8bb7bf5592990e7c": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "75172581104d4f90985af41ac44b9260": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "75770fd10d8b4d0ba78d530eb667893b": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "Alabama",
                    "Arizona",
                    "Arkansas",
                    "California",
                    "Colorado",
                    "Connecticut",
                    "Delaware",
                    "District of Columbia",
                    "Florida",
                    "Georgia",
                    "Hawaii",
                    "Idaho",
                    "Illinois",
                    "Indiana",
                    "Iowa",
                    "Kansas",
                    "Kentucky",
                    "Louisiana",
                    "Maine",
                    "Maryland",
                    "Massachusetts",
                    "Michigan",
                    "Minnesota",
                    "Mississippi",
                    "Missouri",
                    "Montana",
                    "Nebraska",
                    "Nevada",
                    "New Hampshire",
                    "New Jersey",
                    "New Mexico",
                    "New York",
                    "North Carolina",
                    "North Dakota",
                    "Ohio",
                    "Oklahoma",
                    "Oregon",
                    "Pennsylvania",
                    "Puerto Rico",
                    "Rhode Island",
                    "South Carolina",
                    "South Dakota",
                    "Tennessee",
                    "Texas",
                    "Utah",
                    "Vermont",
                    "Virginia",
                    "Washington",
                    "West Virginia",
                    "Wisconsin"
                ],
                "description": "Filing State :",
                "index": 0,
                "layout": "IPY_MODEL_3ac37786169f4010aec1f6cce80ca59b",
                "style": "IPY_MODEL_f4fb0b80ffa84ddf925b2f3e7c77ce1e"
            }
        },
        "75a95063eaae440c9bff336e7b4f2031": {
            "model_name": "FigureModel",
            "model_module": "plotlywidget",
            "model_module_version": "0.9.1",
            "state": {
                "_config": {
                    "plotlyServerURL": "https://plot.ly"
                },
                "_data": [
                    {
                        "marker": {
                            "color": "rgb(26, 118, 255)",
                            "line": {
                                "color": "rgba(100, 10, 255, 1.0)",
                                "width": 2
                            }
                        },
                        "orientation": "v",
                        "type": "bar",
                        "uid": "9e22979c-83b3-4189-a861-79757e398c16",
                        "x": [
                            "Debit Card",
                            "Deposit Account"
                        ],
                        "y": [
                            223,
                            493
                        ]
                    }
                ],
                "_js2py_restyle": {},
                "_js2py_update": {},
                "_last_layout_edit_id": 1,
                "_layout": {
                    "annotations": [
                        {
                            "font": {
                                "color": "red",
                                "size": 10
                            },
                            "showarrow": false,
                            "text": "Source: FINCEN.gov",
                            "x": 1,
                            "xanchor": "right",
                            "xref": "paper",
                            "xshift": 0,
                            "y": -0.15,
                            "yanchor": "auto",
                            "yref": "paper",
                            "yshift": 0
                        }
                    ],
                    "autosize": true,
                    "barmode": "group",
                    "hovermode": "closest",
                    "template": {},
                    "title": {
                        "text": "SAR Filings by State and Product"
                    }
                },
                "_model_module_version": "0.9.1",
                "_py2js_addTraces": {},
                "_py2js_animate": {},
                "_py2js_deleteTraces": {},
                "_py2js_moveTraces": {},
                "_py2js_removeLayoutProps": {},
                "_py2js_removeTraceProps": {},
                "_py2js_restyle": {},
                "_py2js_update": {},
                "_view_count": 0,
                "_view_module_version": "0.9.1"
            }
        },
        "75ec67aaf02f43c0a154c5f8b236b336": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "7662b22548364d6c9fee9f926041ddbd": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "76650e411e544d5995c862d865b727dd": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "2014",
                    "2019",
                    "2015",
                    "2018",
                    "2017",
                    "2016",
                    "2012",
                    "2013"
                ],
                "description": "Date : ",
                "index": 1,
                "layout": "IPY_MODEL_9878ca6982334bb285883dc1a1686e14",
                "style": "IPY_MODEL_20c4916bc510460bb1be1d454f210997"
            }
        },
        "76d0d27363f0409aa1e29c7694d17d86": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "2014",
                    "2019",
                    "2015",
                    "2018",
                    "2017",
                    "2016",
                    "2012",
                    "2013"
                ],
                "description": "Date : ",
                "index": 6,
                "layout": "IPY_MODEL_a926c95d8cb048cea27b76c329c1413e",
                "style": "IPY_MODEL_482f5398d9e546b8a5eec4ccc35b71e4"
            }
        },
        "76fe8c8d60464fac9eb0d1ce84ea48fd": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "770eec173fb445b3bd68a630620475ca": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "77312068d30847d3a746cb10ae9511cc": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "77514344428e475cb8d3a2d759e75c00": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "775df3deb25b4887b36fff003678b6b8": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_521a584c44ef4d1aa69e60b33fa9c046"
                ],
                "layout": "IPY_MODEL_2e1cf8213a4b47159f6f457b9521bac1"
            }
        },
        "77c41ae349144535896851f0049e269f": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_a8c3ebade4d5412bb82fd6656a9f3c32"
                ],
                "layout": "IPY_MODEL_891d0b92ca3f47448df053f6b576765b"
            }
        },
        "7850f6e5058d40309d093ad8844071e4": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "787d94225a864857a4a59552b64731bf": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "78aa9f61def741a4ba2a8f3e10e3f89c": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "78acd5cbbc4a4a5ead67f70b1c332d44": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "790249b865774a9baaaf57008ba7a370": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "790838bb77444a2bb1175ef1af931ed7": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "OCC",
                    "FDIC",
                    "SEC",
                    "FHFA",
                    "CFTC"
                ],
                "description": "Regulator :",
                "index": 0,
                "layout": "IPY_MODEL_8c0ba419b72140b9856e1f7441b31151",
                "style": "IPY_MODEL_8a25fba07abe4728b7a3ddc1053c377d"
            }
        },
        "794fcdf0aaf24e41bb20f72c8d968a7b": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "Alabama",
                    "Arizona",
                    "Arkansas",
                    "California",
                    "Colorado",
                    "Connecticut",
                    "Delaware",
                    "District of Columbia",
                    "Florida",
                    "Georgia",
                    "Hawaii",
                    "Idaho",
                    "Illinois",
                    "Indiana",
                    "Iowa",
                    "Kansas",
                    "Kentucky",
                    "Louisiana",
                    "Maine",
                    "Maryland",
                    "Massachusetts",
                    "Michigan",
                    "Minnesota",
                    "Mississippi",
                    "Missouri",
                    "Montana",
                    "Nebraska",
                    "Nevada",
                    "New Hampshire",
                    "New Jersey",
                    "New Mexico",
                    "New York",
                    "North Carolina",
                    "North Dakota",
                    "Ohio",
                    "Oklahoma",
                    "Oregon",
                    "Pennsylvania",
                    "Puerto Rico",
                    "Rhode Island",
                    "South Carolina",
                    "South Dakota",
                    "Tennessee",
                    "Texas",
                    "Utah",
                    "Vermont",
                    "Virginia",
                    "Washington",
                    "West Virginia",
                    "Wisconsin"
                ],
                "description": "Filing State :",
                "index": 0,
                "layout": "IPY_MODEL_8f1c5543e8ad4dd896b54d67bbe2d22a",
                "style": "IPY_MODEL_b893f2fda6ec456a8bea1cb4944755cc"
            }
        },
        "799da1f29b0b478e8634884d171ff16d": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "Alabama",
                    "Arizona",
                    "Arkansas",
                    "California",
                    "Colorado",
                    "Connecticut",
                    "Delaware",
                    "District of Columbia",
                    "Florida",
                    "Georgia",
                    "Hawaii",
                    "Idaho",
                    "Illinois",
                    "Indiana",
                    "Iowa",
                    "Kansas",
                    "Kentucky",
                    "Louisiana",
                    "Maine",
                    "Maryland",
                    "Massachusetts",
                    "Michigan",
                    "Minnesota",
                    "Mississippi",
                    "Missouri",
                    "Montana",
                    "Nebraska",
                    "Nevada",
                    "New Hampshire",
                    "New Jersey",
                    "New Mexico",
                    "New York",
                    "North Carolina",
                    "North Dakota",
                    "Ohio",
                    "Oklahoma",
                    "Oregon",
                    "Pennsylvania",
                    "Puerto Rico",
                    "Rhode Island",
                    "South Carolina",
                    "South Dakota",
                    "Tennessee",
                    "Texas",
                    "Utah",
                    "Vermont",
                    "Virginia",
                    "Washington",
                    "West Virginia",
                    "Wisconsin"
                ],
                "description": "Filing State :",
                "index": 0,
                "layout": "IPY_MODEL_ed47368a0d3345fd8ca4f1f8153e00e5",
                "style": "IPY_MODEL_0b4bc8892f2845bfbff9bc663236cdea"
            }
        },
        "79fd43fdf79e46f2a499f7a5a691a722": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "Alabama",
                    "Arizona",
                    "Arkansas",
                    "California",
                    "Colorado",
                    "Connecticut",
                    "Delaware",
                    "District of Columbia",
                    "Florida",
                    "Georgia",
                    "Hawaii",
                    "Idaho",
                    "Illinois",
                    "Indiana",
                    "Iowa",
                    "Kansas",
                    "Kentucky",
                    "Louisiana",
                    "Maine",
                    "Maryland",
                    "Massachusetts",
                    "Michigan",
                    "Minnesota",
                    "Mississippi",
                    "Missouri",
                    "Montana",
                    "Nebraska",
                    "Nevada",
                    "New Hampshire",
                    "New Jersey",
                    "New Mexico",
                    "New York",
                    "North Carolina",
                    "North Dakota",
                    "Ohio",
                    "Oklahoma",
                    "Oregon",
                    "Pennsylvania",
                    "Puerto Rico",
                    "Rhode Island",
                    "South Carolina",
                    "South Dakota",
                    "Tennessee",
                    "Texas",
                    "Utah",
                    "Vermont",
                    "Virginia",
                    "Washington",
                    "West Virginia",
                    "Wisconsin"
                ],
                "description": "Filing State :",
                "index": 0,
                "layout": "IPY_MODEL_64dbf1542fe246e79b16f0abb7f41847",
                "style": "IPY_MODEL_477ff576f91e4545b50d0d8d6403ed08"
            }
        },
        "7a27c5674541460e94aa7ffa48a426d5": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "2014",
                    "2019",
                    "2015",
                    "2018",
                    "2017",
                    "2016",
                    "2012",
                    "2013"
                ],
                "description": "Date : ",
                "index": 1,
                "layout": "IPY_MODEL_577eff3bb01a49bcae8af9fd01c3c3f5",
                "style": "IPY_MODEL_128d4169c3704625a78309303d9e9d87"
            }
        },
        "7a30e99dc8274f9db7c2a5b088407819": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "7a49cf26a9204a49b525571e541cd8aa": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "7a6318b811a444be94b48d0867cacf21": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "Alabama",
                    "Arizona",
                    "Arkansas",
                    "California",
                    "Colorado",
                    "Connecticut",
                    "Delaware",
                    "District of Columbia",
                    "Florida",
                    "Georgia",
                    "Hawaii",
                    "Idaho",
                    "Illinois",
                    "Indiana",
                    "Iowa",
                    "Kansas",
                    "Kentucky",
                    "Louisiana",
                    "Maine",
                    "Maryland",
                    "Massachusetts",
                    "Michigan",
                    "Minnesota",
                    "Mississippi",
                    "Missouri",
                    "Montana",
                    "Nebraska",
                    "Nevada",
                    "New Hampshire",
                    "New Jersey",
                    "New Mexico",
                    "New York",
                    "North Carolina",
                    "North Dakota",
                    "Ohio",
                    "Oklahoma",
                    "Oregon",
                    "Pennsylvania",
                    "Puerto Rico",
                    "Rhode Island",
                    "South Carolina",
                    "South Dakota",
                    "Tennessee",
                    "Texas",
                    "Utah",
                    "Vermont",
                    "Virginia",
                    "Washington",
                    "West Virginia",
                    "Wisconsin"
                ],
                "description": "Filing State :",
                "index": 0,
                "layout": "IPY_MODEL_894e2646faaf47fa9d35916e58de057a",
                "style": "IPY_MODEL_3aea042089ae4675adcc0cd4c67527dc"
            }
        },
        "7a6b1888b9144c52b83a8deca3fc466a": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "OCC",
                    "FDIC",
                    "SEC",
                    "FHFA",
                    "CFTC"
                ],
                "description": "Regulator :",
                "index": 0,
                "layout": "IPY_MODEL_a558b8c097c74ec89d9c1ecd27d0eb32",
                "style": "IPY_MODEL_946e57d7351046d0ab5e27c83cdd70a2"
            }
        },
        "7a8a2adddea640a5a361984f9aa7c59d": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "7aa1801f774a4a6bb09b5a41b148d424": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "7ab397e3fd334cd2905c794021e85465": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "7ad11631f3734f5198f7742419b79b7e": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "7af0576aab5449ac9fd1cf9d2b681055": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "7af8fb890cb24e2eae582d1d3eda520e": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "7b25792d334949a091fc85f1e6c28b52": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "7b2bf586e7b848068e8beb7eb5192900": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "7b51ae1458d44ec1a7a8ef3fd60226ff": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "Alabama",
                    "Arizona",
                    "Arkansas",
                    "California",
                    "Colorado",
                    "Connecticut",
                    "Delaware",
                    "District of Columbia",
                    "Florida",
                    "Georgia",
                    "Hawaii",
                    "Idaho",
                    "Illinois",
                    "Indiana",
                    "Iowa",
                    "Kansas",
                    "Kentucky",
                    "Louisiana",
                    "Maine",
                    "Maryland",
                    "Massachusetts",
                    "Michigan",
                    "Minnesota",
                    "Mississippi",
                    "Missouri",
                    "Montana",
                    "Nebraska",
                    "Nevada",
                    "New Hampshire",
                    "New Jersey",
                    "New Mexico",
                    "New York",
                    "North Carolina",
                    "North Dakota",
                    "Ohio",
                    "Oklahoma",
                    "Oregon",
                    "Pennsylvania",
                    "Puerto Rico",
                    "Rhode Island",
                    "South Carolina",
                    "South Dakota",
                    "Tennessee",
                    "Texas",
                    "Utah",
                    "Vermont",
                    "Virginia",
                    "Washington",
                    "West Virginia",
                    "Wisconsin"
                ],
                "description": "Filing State :",
                "index": 0,
                "layout": "IPY_MODEL_17f23f730a2c4f56aec312f50aff71bb",
                "style": "IPY_MODEL_123025abddcf427a887ed1776849e013"
            }
        },
        "7b5f35a9a58447aebc5c1c08f84604d2": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "7baaf4e317cc46838f0d3b2a5e898f88": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "7bb17ef70de2447a842bc5f2f85e6fa6": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "OCC",
                    "FDIC",
                    "SEC",
                    "FHFA",
                    "CFTC"
                ],
                "description": "Regulator :",
                "index": 0,
                "layout": "IPY_MODEL_adb19d9897ae4f94be212c27d08fb72e",
                "style": "IPY_MODEL_65cbc0e278f64be2a9d2e4756597e607"
            }
        },
        "7bd78f4a32f9482b90796ccd8f0b5ca9": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "7bdd732d0ea04c9db16c88f5b28aae58": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "7bf4aad1e2534e829f703dd0ba699e62": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "7c801786fa89478caf3b00a78cd042f6": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "7c9944fd604747eb9c233f54ecf83318": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "7cd9b7648aa4426e87b1383de18916c2": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "7cfd2876e26f4404be60c6f32bb8c550": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "7d05537e9ca341669a8ed3ec98fb7d9a": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "2014",
                    "2019",
                    "2015",
                    "2018",
                    "2017",
                    "2016",
                    "2012",
                    "2013"
                ],
                "description": "Date : ",
                "index": 1,
                "layout": "IPY_MODEL_cc60d3ff7fcc41768310d4b5e0ae3dce",
                "style": "IPY_MODEL_0fde65214bec46df899733f73fff32ee"
            }
        },
        "7d0b45053d914ebfb9e6ff4d8fcecb4f": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "7d1162be884040ebaf9f04f1b7414a07": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "7d87072d6cca44b09d4f64b7ff8e2e30": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "7d91ec870f5d4d55b021fb95d9570c97": {
            "model_name": "FigureModel",
            "model_module": "plotlywidget",
            "model_module_version": "0.9.1",
            "state": {
                "_config": {
                    "plotlyServerURL": "https://plot.ly"
                },
                "_data": [
                    {
                        "hovertext": [
                            "                           Year   Count\nRegulator State                        \nCFTC      New York         2014      84\nFDIC      Alabama          2019     331\n          Arizona          2019     186\n          Arkansas         2019     560\n          California      40331    8778\n          Colorado         2019     712\n          Connecticut      4037     886\n          Delaware        34273   48336\n          Florida         20162    2728\n          Georgia         18149    3055\n          Hawaii           2019     650\n          Idaho            2019     175\n          Illinois        14122    2393\n          Indiana          8074    1344\n          Iowa            14122    1573\n          Kansas           4037     493\n          Kentucky         4037     691\n          Louisiana        8074    2440\n          Maine            2019     577\n          Maryland         8068     561\n          Massachusetts   14122    3640\n          Michigan         4037     476\n          Minnesota        4037     498\n          Mississippi     12107    2325\n          Missouri        16130    1739\n          Montana          2019     324\n          Nebraska        12099    2237\n          Nevada          16131    4792\n          New Hampshire    2019     176\n          New Jersey      14122    2451\n...                         ...     ...\nOCC       Ohio            56448  147585\n          Oklahoma        32255   10561\n          Oregon          34274   10734\n          Pennsylvania    46373   43569\n          Rhode Island    20167    6637\n          South Carolina  18149    9694\n          South Dakota    34282   70376\n          Tennessee       28228   12507\n          Texas           62497  119148\n          Utah            30248   26738\n          Vermont          2019     142\n          Virginia        36288  208722\n          Washington      34274   21786\n          West Virginia   12104    1305\n          Wisconsin       32259    8247\nSEC       Arizona          6047     373\n          California      28235    3240\n          Colorado        14104    1728\n          Connecticut     14122    2093\n          Florida         16135     938\n          Massachusetts   42342    6075\n          Nebraska        26215    2830\n          New Jersey      22178    1663\n          New York        32262    5769\n          Pennsylvania    16130    3075\n          Rhode Island    36297    5476\n          Texas           22187    1428\n          Utah            10076    8051\n          Virginia        14115    1269\n          Washington      16116     966\n\n[117 rows x 2 columns]"
                        ],
                        "orientation": "v",
                        "type": "bar",
                        "uid": "90bcf6e3-2cce-4c16-be94-fe97ced589c2",
                        "x": [
                            "Debit Card",
                            "Deposit Account"
                        ],
                        "y": [
                            223,
                            493
                        ]
                    }
                ],
                "_js2py_pointsCallback": {},
                "_js2py_restyle": {},
                "_js2py_update": {},
                "_last_layout_edit_id": 1,
                "_layout": {
                    "autosize": true,
                    "barmode": "group",
                    "hovermode": "closest",
                    "template": {},
                    "title": {
                        "text": "SAR Filings by State and Product"
                    }
                },
                "_model_module_version": "0.9.1",
                "_py2js_addTraces": {},
                "_py2js_animate": {},
                "_py2js_deleteTraces": {},
                "_py2js_moveTraces": {},
                "_py2js_removeLayoutProps": {},
                "_py2js_removeTraceProps": {},
                "_py2js_restyle": {},
                "_py2js_update": {},
                "_view_count": 0,
                "_view_module_version": "0.9.1"
            }
        },
        "7e5756116a4b4c41bf2dfa5c08233632": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "7e7b69a0287248db9e45ed05c7ebe188": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "Alabama",
                    "Arizona",
                    "Arkansas",
                    "California",
                    "Colorado",
                    "Connecticut",
                    "Delaware",
                    "District of Columbia",
                    "Florida",
                    "Georgia",
                    "Hawaii",
                    "Idaho",
                    "Illinois",
                    "Indiana",
                    "Iowa",
                    "Kansas",
                    "Kentucky",
                    "Louisiana",
                    "Maine",
                    "Maryland",
                    "Massachusetts",
                    "Michigan",
                    "Minnesota",
                    "Mississippi",
                    "Missouri",
                    "Montana",
                    "Nebraska",
                    "Nevada",
                    "New Hampshire",
                    "New Jersey",
                    "New Mexico",
                    "New York",
                    "North Carolina",
                    "North Dakota",
                    "Ohio",
                    "Oklahoma",
                    "Oregon",
                    "Pennsylvania",
                    "Puerto Rico",
                    "Rhode Island",
                    "South Carolina",
                    "South Dakota",
                    "Tennessee",
                    "Texas",
                    "Utah",
                    "Vermont",
                    "Virginia",
                    "Washington",
                    "West Virginia",
                    "Wisconsin"
                ],
                "description": "Filing State :",
                "index": 0,
                "layout": "IPY_MODEL_a8d9c65215434aacb3c8015636bdc47a",
                "style": "IPY_MODEL_c177ee20f4ec4549b057ae5c4fb2e75b"
            }
        },
        "7e8e83962de94fa5b41783d7dfcef6d6": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "7e9271c773204535b16137f43f72b507": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "7eae4bb2da95430b8e4d0ac37ce70bf3": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "7fe04c03cf554125a793e5bc23446b10": {
            "model_name": "VBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_902008a05b184e3d92c7522f4a583a4a",
                    "IPY_MODEL_9094d31e411945b7a413f3029a33f00d",
                    "IPY_MODEL_6686a700a6e34fd39f973c5a9ceb0117"
                ],
                "layout": "IPY_MODEL_2786307617da448dba46a00e82088a6e"
            }
        },
        "80619f6ff6df4ebe90d1695b92e4a90b": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "OCC",
                    "FDIC",
                    "SEC",
                    "FHFA",
                    "CFTC"
                ],
                "description": "Regulator :",
                "index": 0,
                "layout": "IPY_MODEL_c6627040d973404bbe39015e6856e30b",
                "style": "IPY_MODEL_73df7fbe0c1d4c5b88236fe55d8a5275"
            }
        },
        "80719ca806014a5b8e6fd09c480aa944": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "807ca1acee4a4d60860548908ebe2b4e": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "807f65f7974a4fe793b587f6d7502238": {
            "model_name": "VBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_050537fbad4e4afaaa115c080ebd3648",
                    "IPY_MODEL_b02378bdd98c435dbbae96c84734af0e",
                    "IPY_MODEL_87fae2b2281045e19937b018bc2fb14d"
                ],
                "layout": "IPY_MODEL_4af2eda0e1154c3b99651872fdb4d2f9"
            }
        },
        "808b40cec3814f559d6facc6836fdac4": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_00ff31413ff246939fcb61ec5c9ea41c"
                ],
                "layout": "IPY_MODEL_ee11b527dc7c4ed6aa968ea71ef5581d"
            }
        },
        "808d96767edb451184194881d5ac3aac": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "2014",
                    "2019",
                    "2015",
                    "2018",
                    "2017",
                    "2016",
                    "2012",
                    "2013"
                ],
                "description": "Date : ",
                "index": 1,
                "layout": "IPY_MODEL_a7cd1a48897741db8cdad1e686c5583e",
                "style": "IPY_MODEL_6ccbec0fea88445b901d6cfc273511e5"
            }
        },
        "80a9b68e90304d94ac2fd9ba38609820": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "2014",
                    "2019",
                    "2015",
                    "2018",
                    "2017",
                    "2016",
                    "2012",
                    "2013"
                ],
                "description": "Date : ",
                "index": 1,
                "layout": "IPY_MODEL_fdccb8d2bd534fc584c0543e63737204",
                "style": "IPY_MODEL_4ffc3ae7e8a24bb1bcd651a9b5fcad59"
            }
        },
        "80d0c96e2bb04f798361489163f6a4a6": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "80da466e9f434350a2e27ecc4cb69840": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "818be46be5b640858d00388ef068dc9c": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_4b4b08cb21154f6bb8ceecc24839f61b"
                ],
                "layout": "IPY_MODEL_d9b17eb240b247ff8faa0680a34788c5"
            }
        },
        "81b59f11baac4a97840f1d669143f8d2": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_d8ed1f1134b0449ebcdbfe9391691209"
                ],
                "layout": "IPY_MODEL_5d255c9ae18b4678be6f6822c75fc4b6"
            }
        },
        "8206a6c10ee3429cbd22b542ca808ce9": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "Alabama",
                    "Arizona",
                    "Arkansas",
                    "California",
                    "Colorado",
                    "Connecticut",
                    "Delaware",
                    "District of Columbia",
                    "Florida",
                    "Georgia",
                    "Hawaii",
                    "Idaho",
                    "Illinois",
                    "Indiana",
                    "Iowa",
                    "Kansas",
                    "Kentucky",
                    "Louisiana",
                    "Maine",
                    "Maryland",
                    "Massachusetts",
                    "Michigan",
                    "Minnesota",
                    "Mississippi",
                    "Missouri",
                    "Montana",
                    "Nebraska",
                    "Nevada",
                    "New Hampshire",
                    "New Jersey",
                    "New Mexico",
                    "New York",
                    "North Carolina",
                    "North Dakota",
                    "Ohio",
                    "Oklahoma",
                    "Oregon",
                    "Pennsylvania",
                    "Puerto Rico",
                    "Rhode Island",
                    "South Carolina",
                    "South Dakota",
                    "Tennessee",
                    "Texas",
                    "Utah",
                    "Vermont",
                    "Virginia",
                    "Washington",
                    "West Virginia",
                    "Wisconsin"
                ],
                "description": "Filing State :",
                "index": 0,
                "layout": "IPY_MODEL_b5d9ea9608224144b5fbdddfbf2cba5d",
                "style": "IPY_MODEL_00ec21931d1f401298f3f5ccf6cc38c0"
            }
        },
        "8247ea68c4be4a76b7a77eacbf65c8cb": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "82567cec33004447ba7edda6d0778862": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "2014",
                    "2019",
                    "2015",
                    "2018",
                    "2017",
                    "2016",
                    "2012",
                    "2013"
                ],
                "description": "Date : ",
                "index": 1,
                "layout": "IPY_MODEL_0dba18924f9e482998e714de7282a2fe",
                "style": "IPY_MODEL_2a022fb2f6d24d45bc89c19d3362ed93"
            }
        },
        "82ec892b739d4126aa5993188af9dc8e": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "OCC",
                    "FDIC",
                    "SEC",
                    "FHFA",
                    "CFTC"
                ],
                "description": "Regulator :",
                "index": 0,
                "layout": "IPY_MODEL_1af5d72bd81848d8a8e81459ebbbb60b",
                "style": "IPY_MODEL_8973e210ce2a405a9b07c9a3d159616c"
            }
        },
        "82fe6e9fe4444ef28bf16e7d5feae29e": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_bd08f8e2ce6849b3a95abbe678547bd8",
                    "IPY_MODEL_b6f792601b1f4c4db3f400e5e07c0273"
                ],
                "layout": "IPY_MODEL_2bdaf86213754f1f98221f3bc93725a4"
            }
        },
        "83222ac9d7014591ac9b96364e0ef10d": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "8333b5c8f6a1423f881d1410d6513750": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "OCC",
                    "FDIC",
                    "SEC",
                    "FHFA",
                    "CFTC"
                ],
                "description": "Regulator :",
                "index": 0,
                "layout": "IPY_MODEL_941545ee478e4095bd096683e049821e",
                "style": "IPY_MODEL_5043f48916ef4627869f6b00df8797f3"
            }
        },
        "8344b97967dc4a659ca216f17811426f": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "837ac0e944654a2f902e6aec465a5769": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "839db55304ac487db749819fda7ba093": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "83cf376a4c7e494da525a20be79bc0d4": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "83e2d4ff74f5402bbc1dcc3f29b3ebac": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "83e7492d6d3a4253bc7b4a0f123f1038": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "842866ccb7744a329ec42e766c0c922b": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "84515acdb71d42acbbdcf74037fa242b": {
            "model_name": "VBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_aefc795e279a4d13b305d3d03e6532c7",
                    "IPY_MODEL_507387b3fb3242e4b98173e69d26c2ca",
                    "IPY_MODEL_70e4ecada8cb48a1a985300413dc8fe8"
                ],
                "layout": "IPY_MODEL_9e7fdbbdd7ac4fae8654331526fc35f2"
            }
        },
        "848d6a0ff56c4317b48d52193968c3b8": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "849d68ecc58741cab9301e5c4acebcd4": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "84f8e4dc449545c798f1102228e7eb98": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_b1d0b300a1bf48849d30fa28c6dcc543"
                ],
                "layout": "IPY_MODEL_7418b603306d49e385e4eb4d39ed1034"
            }
        },
        "851952bf687845aca91a41f2e4f44af6": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "854bb9f9672549fd8c889f3cc079e01d": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "857eab6713ca4af085589d0964b7ce00": {
            "model_name": "FigureModel",
            "model_module": "plotlywidget",
            "model_module_version": "0.9.1",
            "state": {
                "_config": {
                    "plotlyServerURL": "https://plot.ly"
                },
                "_data": [
                    {
                        "orientation": "v",
                        "type": "bar",
                        "uid": "a6916fde-6ff9-4674-8f6b-56857589550d",
                        "x": [],
                        "y": []
                    }
                ],
                "_js2py_pointsCallback": {},
                "_js2py_restyle": {},
                "_js2py_update": {},
                "_last_layout_edit_id": 2,
                "_last_trace_edit_id": 1,
                "_layout": {
                    "autosize": true,
                    "barmode": "group",
                    "hovermode": "closest",
                    "template": {},
                    "title": {
                        "text": "SAR Filings by State and Product"
                    },
                    "xaxis": {
                        "title": {
                            "text": "SARs Filing Type"
                        }
                    },
                    "yaxis": {
                        "title": {
                            "text": "Number of Filings"
                        }
                    }
                },
                "_model_module_version": "0.9.1",
                "_py2js_addTraces": {},
                "_py2js_animate": {},
                "_py2js_deleteTraces": {},
                "_py2js_moveTraces": {},
                "_py2js_removeLayoutProps": {},
                "_py2js_removeTraceProps": {},
                "_py2js_restyle": {},
                "_view_count": 0,
                "_view_module_version": "0.9.1"
            }
        },
        "85875b7d1754437fa86b9e7b02ac89af": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "OCC",
                    "FDIC",
                    "SEC",
                    "FHFA",
                    "CFTC"
                ],
                "description": "Regulator :",
                "index": 0,
                "layout": "IPY_MODEL_1a499900eb284f1eb055535f3ef618fb",
                "style": "IPY_MODEL_f7b9db2b98f7454c8c9d0eb6dd9124fc"
            }
        },
        "85a25e88a71140b8ba4a7b7c94db2217": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_68b33582cef142a4bbfd5b0cb266a9b7",
                    "IPY_MODEL_80619f6ff6df4ebe90d1695b92e4a90b"
                ],
                "layout": "IPY_MODEL_d0ce5dec552f440592834ebc78e976eb"
            }
        },
        "85b19478fa56488cbcb78e1f4e938f0e": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "85bfabb7d32441929787a9069129a381": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "2014",
                    "2019",
                    "2015",
                    "2018",
                    "2017",
                    "2016",
                    "2012",
                    "2013"
                ],
                "description": "Date : ",
                "index": 1,
                "layout": "IPY_MODEL_e3068ce4b9e24f63b4068ceb6ab31692",
                "style": "IPY_MODEL_bcd78aac7bc1425ba118464395e29f15"
            }
        },
        "85c5d82878db4e368b4b635fcc0b3993": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "86034c0904c64e73a7cca576f59efee2": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "Alabama",
                    "Arizona",
                    "Arkansas",
                    "California",
                    "Colorado",
                    "Connecticut",
                    "Delaware",
                    "District of Columbia",
                    "Florida",
                    "Georgia",
                    "Hawaii",
                    "Idaho",
                    "Illinois",
                    "Indiana",
                    "Iowa",
                    "Kansas",
                    "Kentucky",
                    "Louisiana",
                    "Maine",
                    "Maryland",
                    "Massachusetts",
                    "Michigan",
                    "Minnesota",
                    "Mississippi",
                    "Missouri",
                    "Montana",
                    "Nebraska",
                    "Nevada",
                    "New Hampshire",
                    "New Jersey",
                    "New Mexico",
                    "New York",
                    "North Carolina",
                    "North Dakota",
                    "Ohio",
                    "Oklahoma",
                    "Oregon",
                    "Pennsylvania",
                    "Puerto Rico",
                    "Rhode Island",
                    "South Carolina",
                    "South Dakota",
                    "Tennessee",
                    "Texas",
                    "Utah",
                    "Vermont",
                    "Virginia",
                    "Washington",
                    "West Virginia",
                    "Wisconsin"
                ],
                "description": "Filing State :",
                "index": 0,
                "layout": "IPY_MODEL_aa8b8f5b4653425292e04e6b702a3933",
                "style": "IPY_MODEL_8f2c83cd327b4ff6b75fc44830209079"
            }
        },
        "863d08bac36f401898272a305db8d71e": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "86ab00f63cf541a8bae18e80255ee6b2": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "875bf9fe397b4dd5810fc4d7520851c8": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_3826ebbaf1324939bab3e866a5d88fe8"
                ],
                "layout": "IPY_MODEL_0a546ca655034c27b380776df37326a0"
            }
        },
        "879d8ebc9a1a4008972a8fa30458228f": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "87fae2b2281045e19937b018bc2fb14d": {
            "model_name": "FigureModel",
            "model_module": "plotlywidget",
            "model_module_version": "0.9.1",
            "state": {
                "_config": {
                    "plotlyServerURL": "https://plot.ly"
                },
                "_data": [
                    {
                        "orientation": "v",
                        "text": {
                            "dtype": "float64",
                            "shape": [
                                2
                            ]
                        },
                        "textposition": "inside",
                        "type": "bar",
                        "uid": "a3844751-bb16-4329-9c32-7781aa5cfe04",
                        "x": [
                            "Debit Card",
                            "Deposit Account"
                        ],
                        "y": [
                            223,
                            493
                        ]
                    }
                ],
                "_js2py_restyle": {},
                "_js2py_update": {},
                "_last_layout_edit_id": 1,
                "_layout": {
                    "annotations": [
                        {
                            "font": {
                                "color": "red",
                                "size": 10
                            },
                            "showarrow": false,
                            "text": "Source: FINCEN.gov",
                            "x": 1,
                            "xanchor": "right",
                            "xref": "paper",
                            "xshift": 0,
                            "y": -0.15,
                            "yanchor": "auto",
                            "yref": "paper",
                            "yshift": 0
                        }
                    ],
                    "autosize": true,
                    "barmode": "group",
                    "hovermode": "closest",
                    "template": {},
                    "title": {
                        "text": "SAR Filings by State and Product"
                    }
                },
                "_model_module_version": "0.9.1",
                "_py2js_addTraces": {},
                "_py2js_animate": {},
                "_py2js_deleteTraces": {},
                "_py2js_moveTraces": {},
                "_py2js_removeLayoutProps": {},
                "_py2js_removeTraceProps": {},
                "_py2js_restyle": {},
                "_py2js_update": {},
                "_view_count": 0,
                "_view_module_version": "0.9.1"
            },
            "buffers": [
                {
                    "data": "AAAAAADga0AAAAAAANB+QA==",
                    "path": [
                        "_data",
                        0,
                        "text",
                        "value"
                    ],
                    "encoding": "base64"
                }
            ]
        },
        "885930e0f1094a179ce80b8b04658d9b": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "OCC",
                    "FDIC",
                    "SEC",
                    "FHFA",
                    "CFTC"
                ],
                "description": "Regulator :",
                "index": 0,
                "layout": "IPY_MODEL_4e616b3f0f62427e915de85af674cc82",
                "style": "IPY_MODEL_7bf4aad1e2534e829f703dd0ba699e62"
            }
        },
        "888479d941354ec38eebf7f43489ed67": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_eb47ee6067a548e4a68c07596458e7be"
                ],
                "layout": "IPY_MODEL_6da243f63b5e46b691c91d65fc2fd0fa"
            }
        },
        "88a220c6b9c54dc2a74d4637d0e971d1": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "88cfc98c7b6444a0a279728075a52d31": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "88f975a4e9a84226af9d93509b791abc": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "Alabama",
                    "Arizona",
                    "Arkansas",
                    "California",
                    "Colorado",
                    "Connecticut",
                    "Delaware",
                    "District of Columbia",
                    "Florida",
                    "Georgia",
                    "Hawaii",
                    "Idaho",
                    "Illinois",
                    "Indiana",
                    "Iowa",
                    "Kansas",
                    "Kentucky",
                    "Louisiana",
                    "Maine",
                    "Maryland",
                    "Massachusetts",
                    "Michigan",
                    "Minnesota",
                    "Mississippi",
                    "Missouri",
                    "Montana",
                    "Nebraska",
                    "Nevada",
                    "New Hampshire",
                    "New Jersey",
                    "New Mexico",
                    "New York",
                    "North Carolina",
                    "North Dakota",
                    "Ohio",
                    "Oklahoma",
                    "Oregon",
                    "Pennsylvania",
                    "Puerto Rico",
                    "Rhode Island",
                    "South Carolina",
                    "South Dakota",
                    "Tennessee",
                    "Texas",
                    "Utah",
                    "Vermont",
                    "Virginia",
                    "Washington",
                    "West Virginia",
                    "Wisconsin"
                ],
                "description": "Filing State :",
                "index": 0,
                "layout": "IPY_MODEL_2b80da6f58a14f40aa9f888d2077bc76",
                "style": "IPY_MODEL_1d05ece61e2f46579bb467bdbf172f10"
            }
        },
        "890ab4dff6064d608769a6484bb03ffa": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "891d0b92ca3f47448df053f6b576765b": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "8931f6dc1e804cf9a8986fde2efcda77": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "OCC",
                    "FDIC",
                    "SEC",
                    "FHFA",
                    "CFTC"
                ],
                "description": "Regulator :",
                "index": 0,
                "layout": "IPY_MODEL_db28fd403d9845eeb1741af9f71b9896",
                "style": "IPY_MODEL_631406d68761445bb4d28417718ad106"
            }
        },
        "894e2646faaf47fa9d35916e58de057a": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "895d82e00c3d45c88c08494f58fdaf9e": {
            "model_name": "FigureModel",
            "model_module": "plotlywidget",
            "model_module_version": "0.9.1",
            "state": {
                "_config": {
                    "plotlyServerURL": "https://plot.ly"
                },
                "_data": [
                    {
                        "orientation": "v",
                        "type": "bar",
                        "uid": "17812bc0-c4e1-428b-a833-fb90a2c3c1f7",
                        "x": [
                            "Debit Card",
                            "Deposit Account"
                        ],
                        "y": [
                            223,
                            493
                        ]
                    }
                ],
                "_js2py_restyle": {},
                "_js2py_update": {},
                "_last_layout_edit_id": 1,
                "_layout": {
                    "annotations": [
                        {
                            "font": {
                                "color": "red",
                                "size": 10
                            },
                            "showarrow": false,
                            "text": "Source: FINCEN.gov",
                            "x": 1,
                            "xanchor": "right",
                            "xref": "paper",
                            "xshift": 0,
                            "y": -0.15,
                            "yanchor": "auto",
                            "yref": "paper",
                            "yshift": 0
                        }
                    ],
                    "autosize": true,
                    "barmode": "group",
                    "hovermode": "closest",
                    "template": {},
                    "title": {
                        "text": "SAR Filings by State and Product"
                    }
                },
                "_model_module_version": "0.9.1",
                "_py2js_addTraces": {},
                "_py2js_animate": {},
                "_py2js_deleteTraces": {},
                "_py2js_moveTraces": {},
                "_py2js_removeLayoutProps": {},
                "_py2js_removeTraceProps": {},
                "_py2js_restyle": {},
                "_py2js_update": {},
                "_view_count": 0,
                "_view_module_version": "0.9.1"
            }
        },
        "8973e210ce2a405a9b07c9a3d159616c": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "897457bf3ec54a84830be0a501ae8a59": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "Alabama",
                    "Arizona",
                    "Arkansas",
                    "California",
                    "Colorado",
                    "Connecticut",
                    "Delaware",
                    "District of Columbia",
                    "Florida",
                    "Georgia",
                    "Hawaii",
                    "Idaho",
                    "Illinois",
                    "Indiana",
                    "Iowa",
                    "Kansas",
                    "Kentucky",
                    "Louisiana",
                    "Maine",
                    "Maryland",
                    "Massachusetts",
                    "Michigan",
                    "Minnesota",
                    "Mississippi",
                    "Missouri",
                    "Montana",
                    "Nebraska",
                    "Nevada",
                    "New Hampshire",
                    "New Jersey",
                    "New Mexico",
                    "New York",
                    "North Carolina",
                    "North Dakota",
                    "Ohio",
                    "Oklahoma",
                    "Oregon",
                    "Pennsylvania",
                    "Puerto Rico",
                    "Rhode Island",
                    "South Carolina",
                    "South Dakota",
                    "Tennessee",
                    "Texas",
                    "Utah",
                    "Vermont",
                    "Virginia",
                    "Washington",
                    "West Virginia",
                    "Wisconsin"
                ],
                "description": "Filing State :",
                "index": 0,
                "layout": "IPY_MODEL_bc6e404665924593aa819d1a23b6f494",
                "style": "IPY_MODEL_a5fe07d8d9a14aeba82ab14efdd27121"
            }
        },
        "897c7dc3e5324026bcbc03a237a90108": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "899e3d1001a446eaa7e5bb0a35c05f54": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "8a10ebfb541e4173b44002eeeb3a1e6b": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "8a25fba07abe4728b7a3ddc1053c377d": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "8a2d3b3899f04de7a4b94dbd6e367522": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_f979a5cf4a7d45a98aa2d774d0ce1f0f"
                ],
                "layout": "IPY_MODEL_c6cf91d0d43845ae8add2411b02467dd"
            }
        },
        "8a4a53b371db4f51ac4a6f9b743cff03": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "8a71ebe97e9e44a3b6f1133b160a2f8e": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_9d66f140df6847c0a50449e84d387bd5"
                ],
                "layout": "IPY_MODEL_71b5fe6863fb4d02b81c099c238ebcdb"
            }
        },
        "8aa6ecbd5624448a8e44eb705e83d065": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "8aa70ccf2039482c9b3ba267cf3c01ea": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "OCC",
                    "FDIC",
                    "SEC",
                    "FHFA",
                    "CFTC"
                ],
                "description": "Regulator :",
                "index": 0,
                "layout": "IPY_MODEL_83cf376a4c7e494da525a20be79bc0d4",
                "style": "IPY_MODEL_dd7b2f6901d245faa1f06d4d2cd011f6"
            }
        },
        "8ae3fc9167134d4baea0b0824c8ab0c7": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "8b05cd98b0b949b6961ba83b87dc19c4": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "OCC",
                    "FDIC",
                    "SEC",
                    "FHFA",
                    "CFTC"
                ],
                "description": "Regulator :",
                "index": 0,
                "layout": "IPY_MODEL_962f13ab5b8b4b5ab39c0988750764da",
                "style": "IPY_MODEL_e53655a032c34aa3a717dbe39f07fe53"
            }
        },
        "8b063f2856284c7a8128d0ae87f7b71a": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "8b52292ac991442ab746cccd0eaaa254": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "8b75492536c44ef7b9aadbfb9ade9dd5": {
            "model_name": "FigureModel",
            "model_module": "plotlywidget",
            "model_module_version": "0.9.1",
            "state": {
                "_config": {
                    "plotlyServerURL": "https://plot.ly"
                },
                "_data": [
                    {
                        "marker": {
                            "color": "rgb(26, 118, 255)",
                            "line": {
                                "color": "rgba(100, 10, 205, 1.0)",
                                "width": 2
                            }
                        },
                        "orientation": "v",
                        "type": "bar",
                        "uid": "122e4c9b-fcc7-47de-bb98-adb8057daa52",
                        "x": [
                            "Debit Card",
                            "Deposit Account"
                        ],
                        "y": [
                            223,
                            493
                        ]
                    }
                ],
                "_js2py_pointsCallback": {},
                "_js2py_restyle": {},
                "_js2py_update": {},
                "_last_layout_edit_id": 1,
                "_layout": {
                    "annotations": [
                        {
                            "font": {
                                "color": "red",
                                "size": 10
                            },
                            "showarrow": false,
                            "text": "Source: FINCEN.gov",
                            "x": 1,
                            "xanchor": "right",
                            "xref": "paper",
                            "xshift": 0,
                            "y": -0.15,
                            "yanchor": "auto",
                            "yref": "paper",
                            "yshift": 0
                        }
                    ],
                    "autosize": true,
                    "barmode": "group",
                    "hovermode": "closest",
                    "paper_bgcolor": "whitesmoke",
                    "plot_bgcolor": "whitesmoke",
                    "template": {},
                    "title": {
                        "text": "SAR Filings by State and Product"
                    }
                },
                "_model_module_version": "0.9.1",
                "_py2js_addTraces": {},
                "_py2js_animate": {},
                "_py2js_deleteTraces": {},
                "_py2js_moveTraces": {},
                "_py2js_removeLayoutProps": {},
                "_py2js_removeTraceProps": {},
                "_py2js_restyle": {},
                "_py2js_update": {},
                "_view_count": 0,
                "_view_module_version": "0.9.1"
            }
        },
        "8b8bd823c3684f3392dbd6d2268325c8": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "8be187e89c4740b8935dd260bc1f3a5f": {
            "model_name": "VBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_091747c504d24ee69dca82fba9823216",
                    "IPY_MODEL_530a069520054a238c50febf355bccf2",
                    "IPY_MODEL_895d82e00c3d45c88c08494f58fdaf9e"
                ],
                "layout": "IPY_MODEL_dfa10e528cfd46ccbb1c28e9b2bdfcc1"
            }
        },
        "8be82ee921fd468db7b69fd438e387e0": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "8c0ba419b72140b9856e1f7441b31151": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "8c9217d326ce465aa56b3580c90231e6": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "OCC",
                    "FDIC",
                    "SEC",
                    "FHFA",
                    "CFTC"
                ],
                "description": "Regulator :",
                "index": 0,
                "layout": "IPY_MODEL_f1518b438ce7445dbc3b0171ae42cc6e",
                "style": "IPY_MODEL_70e9bd2e051740179e016159db6032f7"
            }
        },
        "8ce15539b2a1476bae38d1982e1d0bbd": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "8d079daa2f994f01bee4d4160809c4d2": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_b6bbac5394304b74ae9e2a9415e620c7"
                ],
                "layout": "IPY_MODEL_85b19478fa56488cbcb78e1f4e938f0e"
            }
        },
        "8d737c8af1df437c80e84bc4a4358a8a": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "2014",
                    "2019",
                    "2015",
                    "2018",
                    "2017",
                    "2016",
                    "2012",
                    "2013"
                ],
                "description": "Date : ",
                "index": 1,
                "layout": "IPY_MODEL_5e88c8be96214de28173b0827edb80ce",
                "style": "IPY_MODEL_0df7a4c858d34b01960454d84726f45e"
            }
        },
        "8d9e44576f354c608f3d49a338abfa7c": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "8ddee12b2ce54276a0a31e1ab43404f6": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "OCC",
                    "FDIC",
                    "SEC",
                    "FHFA",
                    "CFTC"
                ],
                "description": "Regulator :",
                "index": 0,
                "layout": "IPY_MODEL_961cd42f922a4503b51606c11c16df12",
                "style": "IPY_MODEL_da8b1e38196843119e69fc9005552e09"
            }
        },
        "8deec8f6dbc44001b5ee2e028e48ced1": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "8e519461e1874731a7d77172423e4cfe": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "8e543b26753a437a9d2ab91b1d8673b4": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "8e5b097af95c42a89243592f70d859ed": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "8e5d7cd162c94119864516d98e3191f4": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "8e7f6992a1904296a342e6a437e005f0": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "Alabama",
                    "Arizona",
                    "Arkansas",
                    "California",
                    "Colorado",
                    "Connecticut",
                    "Delaware",
                    "District of Columbia",
                    "Florida",
                    "Georgia",
                    "Hawaii",
                    "Idaho",
                    "Illinois",
                    "Indiana",
                    "Iowa",
                    "Kansas",
                    "Kentucky",
                    "Louisiana",
                    "Maine",
                    "Maryland",
                    "Massachusetts",
                    "Michigan",
                    "Minnesota",
                    "Mississippi",
                    "Missouri",
                    "Montana",
                    "Nebraska",
                    "Nevada",
                    "New Hampshire",
                    "New Jersey",
                    "New Mexico",
                    "New York",
                    "North Carolina",
                    "North Dakota",
                    "Ohio",
                    "Oklahoma",
                    "Oregon",
                    "Pennsylvania",
                    "Puerto Rico",
                    "Rhode Island",
                    "South Carolina",
                    "South Dakota",
                    "Tennessee",
                    "Texas",
                    "Utah",
                    "Vermont",
                    "Virginia",
                    "Washington",
                    "West Virginia",
                    "Wisconsin"
                ],
                "description": "Filing State :",
                "index": 0,
                "layout": "IPY_MODEL_3cd112c5bd954c448b12344d98c630f3",
                "style": "IPY_MODEL_7e5756116a4b4c41bf2dfa5c08233632"
            }
        },
        "8e8271b384324cd39994249a1b1dfb43": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "8eb5290419fc4763a656ff42004891ff": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_55f18b7976854d2f99d7b630501b329d"
                ],
                "layout": "IPY_MODEL_af8880007a204006bdbad33daafb080f"
            }
        },
        "8ef333d1c5a843bbb30f940bd344d2b9": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "8ef4fb5ae7c547428869a904bd0989d8": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "2014",
                    "2019",
                    "2015",
                    "2018",
                    "2017",
                    "2016",
                    "2012",
                    "2013"
                ],
                "description": "Date : ",
                "index": 1,
                "layout": "IPY_MODEL_14808ad46f04413eb5f7622a15cfd133",
                "style": "IPY_MODEL_b61106304b2849649ef957ecb499d790"
            }
        },
        "8efef68fdf7e453ab14e0a8e1ff7d146": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "8f090569de674a4db7138ac41fb166ed": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "8f1c5543e8ad4dd896b54d67bbe2d22a": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "8f2c83cd327b4ff6b75fc44830209079": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "8f54cf4ad72a4c3eb15018e63c080131": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_546c2b4da66b412a8e3d682818b6f6e5"
                ],
                "layout": "IPY_MODEL_d58fec37df884047a0ac7328d7666ebe"
            }
        },
        "8ffd5779ca134fd1bdee87b3854ce6af": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_33a877cf33804baeb3b44113399c6fee",
                    "IPY_MODEL_ed721a5c757a45b2a21e4395b383a96b"
                ],
                "layout": "IPY_MODEL_e6a2bcc3f08b4a9aaa9994ea18ca566e"
            }
        },
        "90082147a74a4c408726267357442111": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "902008a05b184e3d92c7522f4a583a4a": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_11a5de5a7673472091ee8344eae217c5"
                ],
                "layout": "IPY_MODEL_5f8f4233447c4962b7a836234b648d4b"
            }
        },
        "903202039225482e9e7606de498ffbb7": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_fed9e53e5a7644c9a6598351b971a8c6"
                ],
                "layout": "IPY_MODEL_dfa1208b797c4af499da64040a1deddc"
            }
        },
        "9094d31e411945b7a413f3029a33f00d": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_e9957da46c2049da9f87e94c02fee7d8",
                    "IPY_MODEL_4624452a77a64219bddf51a10d1e8d36"
                ],
                "layout": "IPY_MODEL_67f994923765424e903d1793be35c9b7"
            }
        },
        "9117c01a7e0947469410d6f4eb2bd783": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "OCC",
                    "FDIC",
                    "SEC",
                    "FHFA",
                    "CFTC"
                ],
                "description": "Regulator :",
                "index": 0,
                "layout": "IPY_MODEL_dd745b119b9540eeb9bd119f7a4a7831",
                "style": "IPY_MODEL_ba5071afac914b6397296793e77ccbe5"
            }
        },
        "9169f640f28d4ec7b5524a8b06431313": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "91ac0dac4e234e0897b1197eef744a8d": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "91aef7ee3a9144349a83df8c4e572a68": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "91af142ad4184bbe9aeb65589f109b84": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "91b85afbc3454ef79e18b3f6507c69e5": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_e79d27b1dcd34bd4b21e81ba021bb9b1"
                ],
                "layout": "IPY_MODEL_50bb1b398897457998881254951815fe"
            }
        },
        "92570cc2605f4a2b81dc085cbfeca3c9": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "Alabama",
                    "Arizona",
                    "Arkansas",
                    "California",
                    "Colorado",
                    "Connecticut",
                    "Delaware",
                    "District of Columbia",
                    "Florida",
                    "Georgia",
                    "Hawaii",
                    "Idaho",
                    "Illinois",
                    "Indiana",
                    "Iowa",
                    "Kansas",
                    "Kentucky",
                    "Louisiana",
                    "Maine",
                    "Maryland",
                    "Massachusetts",
                    "Michigan",
                    "Minnesota",
                    "Mississippi",
                    "Missouri",
                    "Montana",
                    "Nebraska",
                    "Nevada",
                    "New Hampshire",
                    "New Jersey",
                    "New Mexico",
                    "New York",
                    "North Carolina",
                    "North Dakota",
                    "Ohio",
                    "Oklahoma",
                    "Oregon",
                    "Pennsylvania",
                    "Puerto Rico",
                    "Rhode Island",
                    "South Carolina",
                    "South Dakota",
                    "Tennessee",
                    "Texas",
                    "Utah",
                    "Vermont",
                    "Virginia",
                    "Washington",
                    "West Virginia",
                    "Wisconsin"
                ],
                "description": "Filing State :",
                "index": 0,
                "layout": "IPY_MODEL_354a7dc97b8b43fc820e99b1ea11875e",
                "style": "IPY_MODEL_cfaf7b3ca54d4704a1847523413f8fdd"
            }
        },
        "92654ec1cd654c7a80cfe787f4a61a53": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "928178ea30c44c25b711d7a790cafad4": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "2014",
                    "2019",
                    "2015",
                    "2018",
                    "2017",
                    "2016",
                    "2012",
                    "2013"
                ],
                "description": "Date : ",
                "index": 1,
                "layout": "IPY_MODEL_a59ff9fdf8ba4d629a57ffa7f5e0ace5",
                "style": "IPY_MODEL_21163b0d6db944509808dfb1ea135499"
            }
        },
        "92bd33e977f444f1998075c78033710a": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "92f1aafedf034fbfb9170f8ae092eb79": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "93219b18757049dc8fb7834b6b9baca1": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "OCC",
                    "FDIC",
                    "SEC",
                    "FHFA",
                    "CFTC"
                ],
                "description": "Regulator :",
                "index": 0,
                "layout": "IPY_MODEL_3fcf39c849cb46a4ba4d533f799c8f07",
                "style": "IPY_MODEL_e6bbb82f8a6345b6a7ee30e51aad94ac"
            }
        },
        "940919425469493d841070dc80a140b5": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "Alabama",
                    "Arizona",
                    "Arkansas",
                    "California",
                    "Colorado",
                    "Connecticut",
                    "Delaware",
                    "District of Columbia",
                    "Florida",
                    "Georgia",
                    "Hawaii",
                    "Idaho",
                    "Illinois",
                    "Indiana",
                    "Iowa",
                    "Kansas",
                    "Kentucky",
                    "Louisiana",
                    "Maine",
                    "Maryland",
                    "Massachusetts",
                    "Michigan",
                    "Minnesota",
                    "Mississippi",
                    "Missouri",
                    "Montana",
                    "Nebraska",
                    "Nevada",
                    "New Hampshire",
                    "New Jersey",
                    "New Mexico",
                    "New York",
                    "North Carolina",
                    "North Dakota",
                    "Ohio",
                    "Oklahoma",
                    "Oregon",
                    "Pennsylvania",
                    "Puerto Rico",
                    "Rhode Island",
                    "South Carolina",
                    "South Dakota",
                    "Tennessee",
                    "Texas",
                    "Utah",
                    "Vermont",
                    "Virginia",
                    "Washington",
                    "West Virginia",
                    "Wisconsin"
                ],
                "description": "Filing State :",
                "index": 0,
                "layout": "IPY_MODEL_a4a68558d14640d9b2867889ac24d6ab",
                "style": "IPY_MODEL_298772d169b04ed18ce29acf8389e934"
            }
        },
        "941545ee478e4095bd096683e049821e": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "942de696def14024bf8d0e52c98d694b": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_794fcdf0aaf24e41bb20f72c8d968a7b",
                    "IPY_MODEL_62fea995ba5a40bfb858a7208ab89f60"
                ],
                "layout": "IPY_MODEL_334fa97fe0e34f72b988a78cd8fc99ba"
            }
        },
        "946e57d7351046d0ab5e27c83cdd70a2": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "95081cb893304eefa1a6907ab5eede12": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "9509df825a814c99986be8b4c3685c6e": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "9543e56e5bf940d49bdfd40245990b0d": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "959ee28cc65c4063a4d5c9ff420d8204": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "95d2ab86984b4872a92d4f49cb98b04d": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "961cd42f922a4503b51606c11c16df12": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "9620183350574939b91f9d43f6a5b071": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "962f13ab5b8b4b5ab39c0988750764da": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "96487ddd7a894978851c0647ef9cee1f": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "9669ffa214944d298dc9c88d0b7ec2ac": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "96b9df678a1144219019abe4036e0699": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_08fc92471463413495150a9c1047262f"
                ],
                "layout": "IPY_MODEL_75172581104d4f90985af41ac44b9260"
            }
        },
        "96bada15df72451596447047f3b987e1": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "970ae6d5003b4f8c9fa178bb29f200e6": {
            "model_name": "VBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_dd599a8a21bd453c96e53cd6b02fdfd5",
                    "IPY_MODEL_59ab32205c1e4dd6966e45d5bcc84bd8",
                    "IPY_MODEL_ed840ba31f224f4f9030196592a953a7"
                ],
                "layout": "IPY_MODEL_074b7b8ee4c24962b3abbfb56c442481"
            }
        },
        "977a63e6e7a247efb652ae796b44fba8": {
            "model_name": "FigureModel",
            "model_module": "plotlywidget",
            "model_module_version": "0.9.1",
            "state": {
                "_config": {
                    "plotlyServerURL": "https://plot.ly"
                },
                "_data": [
                    {
                        "marker": {
                            "color": "rgb(26, 118, 255)",
                            "line": {
                                "color": "rgba(100, 10, 205, 1.0)",
                                "width": 2
                            }
                        },
                        "orientation": "v",
                        "type": "bar",
                        "uid": "a8e1123f-50dd-4861-a63a-1fe033dbb282",
                        "x": [
                            "Debit Card",
                            "Deposit Account"
                        ],
                        "y": [
                            223,
                            493
                        ]
                    }
                ],
                "_js2py_restyle": {},
                "_js2py_update": {},
                "_last_layout_edit_id": 7,
                "_last_trace_edit_id": 6,
                "_layout": {
                    "annotations": [
                        {
                            "font": {
                                "color": "red",
                                "size": 10
                            },
                            "showarrow": false,
                            "text": "Source: FINCEN.gov",
                            "x": 1,
                            "xanchor": "right",
                            "xref": "paper",
                            "xshift": 0,
                            "y": -0.15,
                            "yanchor": "auto",
                            "yref": "paper",
                            "yshift": 0
                        }
                    ],
                    "autosize": true,
                    "barmode": "group",
                    "hovermode": "closest",
                    "paper_bgcolor": "whitesmoke",
                    "plot_bgcolor": "whitesmoke",
                    "shapes": [
                        {
                            "line": {
                                "color": "RoyalBlue"
                            },
                            "type": "rect",
                            "x0": 0,
                            "x1": 0,
                            "y0": 0,
                            "y1": 0
                        }
                    ],
                    "template": {},
                    "title": {
                        "text": "SAR Filings by State and Product"
                    },
                    "xaxis": {
                        "title": {
                            "text": "SARs Filing Type"
                        }
                    },
                    "yaxis": {
                        "title": {
                            "text": "Number of Filings"
                        }
                    }
                },
                "_model_module_version": "0.9.1",
                "_py2js_addTraces": {},
                "_py2js_animate": {},
                "_py2js_deleteTraces": {},
                "_py2js_moveTraces": {},
                "_py2js_removeLayoutProps": {},
                "_py2js_removeTraceProps": {},
                "_py2js_restyle": {},
                "_view_count": 0,
                "_view_module_version": "0.9.1"
            }
        },
        "982835a8ac334486a6371f7660ede82e": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "983f5588cf744e899318026abb479ae2": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "9878ca6982334bb285883dc1a1686e14": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "987c449cb29b4f0d9b037832ab394a15": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "Alabama",
                    "Arizona",
                    "Arkansas",
                    "California",
                    "Colorado",
                    "Connecticut",
                    "Delaware",
                    "District of Columbia",
                    "Florida",
                    "Georgia",
                    "Hawaii",
                    "Idaho",
                    "Illinois",
                    "Indiana",
                    "Iowa",
                    "Kansas",
                    "Kentucky",
                    "Louisiana",
                    "Maine",
                    "Maryland",
                    "Massachusetts",
                    "Michigan",
                    "Minnesota",
                    "Mississippi",
                    "Missouri",
                    "Montana",
                    "Nebraska",
                    "Nevada",
                    "New Hampshire",
                    "New Jersey",
                    "New Mexico",
                    "New York",
                    "North Carolina",
                    "North Dakota",
                    "Ohio",
                    "Oklahoma",
                    "Oregon",
                    "Pennsylvania",
                    "Puerto Rico",
                    "Rhode Island",
                    "South Carolina",
                    "South Dakota",
                    "Tennessee",
                    "Texas",
                    "Utah",
                    "Vermont",
                    "Virginia",
                    "Washington",
                    "West Virginia",
                    "Wisconsin"
                ],
                "description": "Filing State :",
                "index": 31,
                "layout": "IPY_MODEL_d0686bec7011499d9eb716cb70300a2d",
                "style": "IPY_MODEL_bf78859c2c0647889a0922895f4ad8e2"
            }
        },
        "98ec042639214716afdedaa69dfeb1f0": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "2014",
                    "2019",
                    "2015",
                    "2018",
                    "2017",
                    "2016",
                    "2012",
                    "2013"
                ],
                "description": "Date : ",
                "index": 1,
                "layout": "IPY_MODEL_bb6666a020c0462d94c17d48e774cddd",
                "style": "IPY_MODEL_5c490978d84b47d7a5732f8d6c76232f"
            }
        },
        "9943dd49b4834195acd96f28b2d16b59": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "995bea200dd64f1c8efd460543a268f5": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "998e83674b4440548bf30ce12aeea4df": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_1ab690206aa2436faea4ad8bdd6cab2a",
                    "IPY_MODEL_688521878d414a3e9e3e81b1e0402ec7"
                ],
                "layout": "IPY_MODEL_b85c39b2849041498606a2136c27eabe"
            }
        },
        "99c394d8201e4f5fb5ad720aefcd7a8a": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "9a399e6326f54a058b352daedf60ce76": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "Alabama",
                    "Arizona",
                    "Arkansas",
                    "California",
                    "Colorado",
                    "Connecticut",
                    "Delaware",
                    "District of Columbia",
                    "Florida",
                    "Georgia",
                    "Hawaii",
                    "Idaho",
                    "Illinois",
                    "Indiana",
                    "Iowa",
                    "Kansas",
                    "Kentucky",
                    "Louisiana",
                    "Maine",
                    "Maryland",
                    "Massachusetts",
                    "Michigan",
                    "Minnesota",
                    "Mississippi",
                    "Missouri",
                    "Montana",
                    "Nebraska",
                    "Nevada",
                    "New Hampshire",
                    "New Jersey",
                    "New Mexico",
                    "New York",
                    "North Carolina",
                    "North Dakota",
                    "Ohio",
                    "Oklahoma",
                    "Oregon",
                    "Pennsylvania",
                    "Puerto Rico",
                    "Rhode Island",
                    "South Carolina",
                    "South Dakota",
                    "Tennessee",
                    "Texas",
                    "Utah",
                    "Vermont",
                    "Virginia",
                    "Washington",
                    "West Virginia",
                    "Wisconsin"
                ],
                "description": "Filing State :",
                "index": 0,
                "layout": "IPY_MODEL_e0789737760445cf9af09b36764bc194",
                "style": "IPY_MODEL_96487ddd7a894978851c0647ef9cee1f"
            }
        },
        "9a4d9dfc27df41fb80cc94f5bee2a189": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_333255d236f040219e9f0bbe8d6b8dbe"
                ],
                "layout": "IPY_MODEL_30980baab8fa4c558bbfd849f08ee5ea"
            }
        },
        "9abbfe66553740d88412b7209426e00a": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_3fefff7268b5438791967a8a9c539106",
                    "IPY_MODEL_c859537ff8734426892fce93e64c9fa2"
                ],
                "layout": "IPY_MODEL_cebc6309a2cb49cf93568365a8cf42bd"
            }
        },
        "9ac536a125f1416c90490c2d5a42d949": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "9b094999c35f40fe8aa8608a71a16d94": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_0754e8becfa14e14bbc4cff147b3910f"
                ],
                "layout": "IPY_MODEL_c795b0a64558421d806e39e68f7ca100"
            }
        },
        "9b59176e0ecd474da91a28330dd5c8fc": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_da581f49010e4df9ad76ca007c29f24a",
                    "IPY_MODEL_fb1d081ff0874208aa475dcf14bf3378"
                ],
                "layout": "IPY_MODEL_d532b425d6e34324b528454c4275e2aa"
            }
        },
        "9b8e81eb229641c3815a91538d116081": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "9be1525cbc5f4c2b8f71feb8f0425e81": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_82567cec33004447ba7edda6d0778862"
                ],
                "layout": "IPY_MODEL_dc75f7483f7044298afb3029121eebe0"
            }
        },
        "9be9b7518468469f89d5e56f7d3668b6": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "2014",
                    "2019",
                    "2015",
                    "2018",
                    "2017",
                    "2016",
                    "2012",
                    "2013"
                ],
                "description": "Date : ",
                "index": 1,
                "layout": "IPY_MODEL_bab5b26a07534e6298296501f59a79dd",
                "style": "IPY_MODEL_4f98e24e0c1b4bb5baaabe84212f76f0"
            }
        },
        "9c0c5cb345134cadbe267b5fec4d8221": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "9c526ec505d5435f9448341f5e952460": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "Alabama",
                    "Arizona",
                    "Arkansas",
                    "California",
                    "Colorado",
                    "Connecticut",
                    "Delaware",
                    "District of Columbia",
                    "Florida",
                    "Georgia",
                    "Hawaii",
                    "Idaho",
                    "Illinois",
                    "Indiana",
                    "Iowa",
                    "Kansas",
                    "Kentucky",
                    "Louisiana",
                    "Maine",
                    "Maryland",
                    "Massachusetts",
                    "Michigan",
                    "Minnesota",
                    "Mississippi",
                    "Missouri",
                    "Montana",
                    "Nebraska",
                    "Nevada",
                    "New Hampshire",
                    "New Jersey",
                    "New Mexico",
                    "New York",
                    "North Carolina",
                    "North Dakota",
                    "Ohio",
                    "Oklahoma",
                    "Oregon",
                    "Pennsylvania",
                    "Puerto Rico",
                    "Rhode Island",
                    "South Carolina",
                    "South Dakota",
                    "Tennessee",
                    "Texas",
                    "Utah",
                    "Vermont",
                    "Virginia",
                    "Washington",
                    "West Virginia",
                    "Wisconsin"
                ],
                "description": "Filing State :",
                "index": 0,
                "layout": "IPY_MODEL_848d6a0ff56c4317b48d52193968c3b8",
                "style": "IPY_MODEL_352f174550d44aa18ed15e1d6a9345c9"
            }
        },
        "9c711bd95d714b1c9103262bd9b6c1cc": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "9d1e31f0703346c48843aa46f223e998": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "9d202069215e453699038f374144d0ad": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "9d4444b76bdf44b68f3273ab518608f0": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "9d4eb723ee124acdb3f783a9de61713d": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "Alabama",
                    "Arizona",
                    "Arkansas",
                    "California",
                    "Colorado",
                    "Connecticut",
                    "Delaware",
                    "District of Columbia",
                    "Florida",
                    "Georgia",
                    "Hawaii",
                    "Idaho",
                    "Illinois",
                    "Indiana",
                    "Iowa",
                    "Kansas",
                    "Kentucky",
                    "Louisiana",
                    "Maine",
                    "Maryland",
                    "Massachusetts",
                    "Michigan",
                    "Minnesota",
                    "Mississippi",
                    "Missouri",
                    "Montana",
                    "Nebraska",
                    "Nevada",
                    "New Hampshire",
                    "New Jersey",
                    "New Mexico",
                    "New York",
                    "North Carolina",
                    "North Dakota",
                    "Ohio",
                    "Oklahoma",
                    "Oregon",
                    "Pennsylvania",
                    "Puerto Rico",
                    "Rhode Island",
                    "South Carolina",
                    "South Dakota",
                    "Tennessee",
                    "Texas",
                    "Utah",
                    "Vermont",
                    "Virginia",
                    "Washington",
                    "West Virginia",
                    "Wisconsin"
                ],
                "description": "Filing State :",
                "index": 0,
                "layout": "IPY_MODEL_1f8136e5c9bb4d228d6245a8d4168466",
                "style": "IPY_MODEL_6092d7bb441a4504a4408eb6a18e9fa1"
            }
        },
        "9d533c674e19409ba0afc87a4bb368d5": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "Alabama",
                    "Arizona",
                    "Arkansas",
                    "California",
                    "Colorado",
                    "Connecticut",
                    "Delaware",
                    "District of Columbia",
                    "Florida",
                    "Georgia",
                    "Hawaii",
                    "Idaho",
                    "Illinois",
                    "Indiana",
                    "Iowa",
                    "Kansas",
                    "Kentucky",
                    "Louisiana",
                    "Maine",
                    "Maryland",
                    "Massachusetts",
                    "Michigan",
                    "Minnesota",
                    "Mississippi",
                    "Missouri",
                    "Montana",
                    "Nebraska",
                    "Nevada",
                    "New Hampshire",
                    "New Jersey",
                    "New Mexico",
                    "New York",
                    "North Carolina",
                    "North Dakota",
                    "Ohio",
                    "Oklahoma",
                    "Oregon",
                    "Pennsylvania",
                    "Puerto Rico",
                    "Rhode Island",
                    "South Carolina",
                    "South Dakota",
                    "Tennessee",
                    "Texas",
                    "Utah",
                    "Vermont",
                    "Virginia",
                    "Washington",
                    "West Virginia",
                    "Wisconsin"
                ],
                "description": "Filing State :",
                "index": 0,
                "layout": "IPY_MODEL_ae336d20844d4b519e83dd51fff8780c",
                "style": "IPY_MODEL_9e083b8c1b55430187fc558ff9674678"
            }
        },
        "9d610417f92947a78bb73786ffe518c5": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "9d66f140df6847c0a50449e84d387bd5": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "2014",
                    "2019",
                    "2015",
                    "2018",
                    "2017",
                    "2016",
                    "2012",
                    "2013"
                ],
                "description": "Date : ",
                "index": 1,
                "layout": "IPY_MODEL_334dc05a00be4fa1bce3ee9141ee5b20",
                "style": "IPY_MODEL_b934b9fba80b4c858be3db6b0e4c3e5b"
            }
        },
        "9d6d5ece1afa454a89fdbe763f7c3b68": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_799da1f29b0b478e8634884d171ff16d",
                    "IPY_MODEL_080005fb6b374432aa280a83aa9c72c2"
                ],
                "layout": "IPY_MODEL_a452a14d6bf241bdbb3896b6e4f1da5e"
            }
        },
        "9d817ec4f59c4590aba8ab6c8098bcd5": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "9d99adb14e95424aa3793f17ab36d90e": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "9e083b8c1b55430187fc558ff9674678": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "9e0f47d7abf74088824e918a9e9ac939": {
            "model_name": "FigureModel",
            "model_module": "plotlywidget",
            "model_module_version": "0.9.1",
            "state": {
                "_config": {
                    "plotlyServerURL": "https://plot.ly"
                },
                "_data": [
                    {
                        "marker": {
                            "color": "rgb(26, 118, 255)",
                            "line": {
                                "color": "rgba(100, 10, 205, 1.0)",
                                "width": 2
                            }
                        },
                        "orientation": "v",
                        "type": "bar",
                        "uid": "8171ed10-02a8-40fa-92c9-ddc9c13e725a",
                        "x": [
                            "Debit Card",
                            "Deposit Account"
                        ],
                        "y": [
                            223,
                            493
                        ]
                    }
                ],
                "_js2py_pointsCallback": {},
                "_js2py_restyle": {},
                "_js2py_update": {},
                "_last_layout_edit_id": 1,
                "_layout": {
                    "annotations": [
                        {
                            "font": {
                                "color": "red",
                                "size": 10
                            },
                            "showarrow": false,
                            "text": "Source: FINCEN.gov",
                            "x": 1,
                            "xanchor": "right",
                            "xref": "paper",
                            "xshift": 0,
                            "y": -0.15,
                            "yanchor": "auto",
                            "yref": "paper",
                            "yshift": 0
                        }
                    ],
                    "autosize": true,
                    "barmode": "group",
                    "hovermode": "closest",
                    "paper_bgcolor": "whitesmoke",
                    "plot_bgcolor": "whitesmoke",
                    "shapes": [
                        {
                            "line": {
                                "color": "RoyalBlue"
                            },
                            "type": "rect",
                            "x0": 0,
                            "x1": 0,
                            "y0": 0,
                            "y1": 0
                        }
                    ],
                    "template": {},
                    "title": {
                        "text": "Number SAR Filings by State and Product"
                    }
                },
                "_model_module_version": "0.9.1",
                "_py2js_addTraces": {},
                "_py2js_animate": {},
                "_py2js_deleteTraces": {},
                "_py2js_moveTraces": {},
                "_py2js_removeLayoutProps": {},
                "_py2js_removeTraceProps": {},
                "_py2js_restyle": {},
                "_py2js_update": {},
                "_view_count": 1,
                "_view_module_version": "0.9.1"
            }
        },
        "9e37205cafd941be8b6def825bc04ce2": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "9e55d3c8cc9f43c29c59268988ce903b": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "Alabama",
                    "Arizona",
                    "Arkansas",
                    "California",
                    "Colorado",
                    "Connecticut",
                    "Delaware",
                    "District of Columbia",
                    "Florida",
                    "Georgia",
                    "Hawaii",
                    "Idaho",
                    "Illinois",
                    "Indiana",
                    "Iowa",
                    "Kansas",
                    "Kentucky",
                    "Louisiana",
                    "Maine",
                    "Maryland",
                    "Massachusetts",
                    "Michigan",
                    "Minnesota",
                    "Mississippi",
                    "Missouri",
                    "Montana",
                    "Nebraska",
                    "Nevada",
                    "New Hampshire",
                    "New Jersey",
                    "New Mexico",
                    "New York",
                    "North Carolina",
                    "North Dakota",
                    "Ohio",
                    "Oklahoma",
                    "Oregon",
                    "Pennsylvania",
                    "Puerto Rico",
                    "Rhode Island",
                    "South Carolina",
                    "South Dakota",
                    "Tennessee",
                    "Texas",
                    "Utah",
                    "Vermont",
                    "Virginia",
                    "Washington",
                    "West Virginia",
                    "Wisconsin"
                ],
                "description": "Filing State :",
                "index": 0,
                "layout": "IPY_MODEL_1deb3f2ce9c04b96804ea5ef14bbc7f1",
                "style": "IPY_MODEL_0f231e76d3f941c89e22df5a0a87dfe4"
            }
        },
        "9e7fdbbdd7ac4fae8654331526fc35f2": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "9ee21ebd3b7d40dcbaaaedb88abd63b3": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "2014",
                    "2019",
                    "2015",
                    "2018",
                    "2017",
                    "2016",
                    "2012",
                    "2013"
                ],
                "description": "Date : ",
                "index": 1,
                "layout": "IPY_MODEL_e1cd11e07d84402da33f5489992bdd85",
                "style": "IPY_MODEL_3a3a5b33297f46a4b0c45882740c3b1a"
            }
        },
        "9f4dab769a6b48819222133010db35d6": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "9f54c61112a64be299c79d1d491de9d8": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "9f61922450eb493880e53c2048827aa9": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "9f6f97b700d243828e8918addf493f52": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "9fa3dd17fb554613a49c88444ac8e6f0": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "9fdf0cc6061d4b77a15b961ba360604b": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "a019e52681c44126b2779df694824942": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_38ac83726b064afab433dddd28ae0dc1",
                    "IPY_MODEL_cdab4393930f4a0892d72282e0bcd5ad"
                ],
                "layout": "IPY_MODEL_f88a6b6c63ae438ea9fb0a9211436a9e"
            }
        },
        "a024c3943fbe4982b429e980a60ede7e": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "a05ee602e2e6447c92035d84293e16ef": {
            "model_name": "VBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_888479d941354ec38eebf7f43489ed67",
                    "IPY_MODEL_daf39203a2fa4307a0616aa115a6ff9c",
                    "IPY_MODEL_519f0c1ebba04d05bde3ba66c55975ce"
                ],
                "layout": "IPY_MODEL_7cd9b7648aa4426e87b1383de18916c2"
            }
        },
        "a0b959b83c894d6c9eba1c7ffe6b84d1": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "a1036af429a143769e17c0c72bdd3154": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_6dc3b32ec0be4898a79b76d36edd1179",
                    "IPY_MODEL_4dca70825dea44a1b816e3922f10e36b"
                ],
                "layout": "IPY_MODEL_06b022b61b7546cd963dd2730928cf91"
            }
        },
        "a1a350e96c4042b8b8e4c62e37e1d126": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "OCC",
                    "FDIC",
                    "SEC",
                    "FHFA",
                    "CFTC"
                ],
                "description": "Regulator :",
                "index": 0,
                "layout": "IPY_MODEL_bf177b6a538342389dbb838d6171e04d",
                "style": "IPY_MODEL_50a972039a324c7ba339eee4768bd67e"
            }
        },
        "a1f3e500c93c467f8f1451d80ed9d5c4": {
            "model_name": "FigureModel",
            "model_module": "plotlywidget",
            "model_module_version": "0.9.1",
            "state": {
                "_config": {
                    "plotlyServerURL": "https://plot.ly"
                },
                "_data": [
                    {
                        "marker": {
                            "color": "rgb(26, 118, 255)",
                            "line": {
                                "color": "rgba(100, 20, 255, 1.0)",
                                "width": 2
                            }
                        },
                        "orientation": "v",
                        "type": "bar",
                        "uid": "74d56201-28b5-4267-a554-8bee5c2b25e1",
                        "x": [
                            "Debit Card",
                            "Deposit Account"
                        ],
                        "y": [
                            223,
                            493
                        ]
                    }
                ],
                "_js2py_restyle": {},
                "_js2py_update": {},
                "_last_layout_edit_id": 1,
                "_layout": {
                    "annotations": [
                        {
                            "font": {
                                "color": "red",
                                "size": 10
                            },
                            "showarrow": false,
                            "text": "Source: FINCEN.gov",
                            "x": 1,
                            "xanchor": "right",
                            "xref": "paper",
                            "xshift": 0,
                            "y": -0.15,
                            "yanchor": "auto",
                            "yref": "paper",
                            "yshift": 0
                        }
                    ],
                    "autosize": true,
                    "barmode": "group",
                    "hovermode": "closest",
                    "template": {},
                    "title": {
                        "text": "SAR Filings by State and Product"
                    }
                },
                "_model_module_version": "0.9.1",
                "_py2js_addTraces": {},
                "_py2js_animate": {},
                "_py2js_deleteTraces": {},
                "_py2js_moveTraces": {},
                "_py2js_removeLayoutProps": {},
                "_py2js_removeTraceProps": {},
                "_py2js_restyle": {},
                "_py2js_update": {},
                "_view_count": 0,
                "_view_module_version": "0.9.1"
            }
        },
        "a220c9b90e9b4e4aa15e0b40e6c837d2": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "a223152396384cffbe70bfa5572b91aa": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_fde64528af2242129ad1c4036603aa39"
                ],
                "layout": "IPY_MODEL_6041ea7cfa7946a386a7a6a50ef87a16"
            }
        },
        "a26c685822e84592b9176d3fd36c63e9": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "a284ec6d339f49259a9301ea8be28b08": {
            "model_name": "VBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_2f7a2b03a36a45059740ec5b00a99df4",
                    "IPY_MODEL_eb3744bdf58a4aa6ab173235bddace8a",
                    "IPY_MODEL_d4f383e047b54676828fa775cad20580"
                ],
                "layout": "IPY_MODEL_e3a1e01f6a0a4bfaae26945d091da03f"
            }
        },
        "a2c733d59b3b4eaf88887d531d6f2ac3": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_132102aa69f649deb65ecd4e67286bdf"
                ],
                "layout": "IPY_MODEL_bb6fe6834dfd47bc8905cd99daa04fa6"
            }
        },
        "a30722e8eb324b07b0249b65eb43fbb2": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "a34b768bc770461bb09be42cb3242170": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "a3af30c841134eefb2caa73ef02d9b16": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "a3c732551ca54891a52443d98d7990e0": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "a3cdf5d52f4141f893a068f7db2686de": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "a40b4173d4c7429ea699f45ff19e4baa": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "OCC",
                    "FDIC",
                    "SEC",
                    "FHFA",
                    "CFTC"
                ],
                "description": "Regulator :",
                "index": 0,
                "layout": "IPY_MODEL_e5652cc3b2254469ab31441f8273206d",
                "style": "IPY_MODEL_c14d83ecaf6c426a814c15e68b63b381"
            }
        },
        "a4127e03e95c4b86bf4e898688d19cd6": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "a452a14d6bf241bdbb3896b6e4f1da5e": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "a4645835e3de488f860e1bc734fb0cd4": {
            "model_name": "FigureModel",
            "model_module": "plotlywidget",
            "model_module_version": "0.9.1",
            "state": {
                "_config": {
                    "plotlyServerURL": "https://plot.ly"
                },
                "_data": [
                    {
                        "hovertext": [
                            "              Year    Count\nRegulator                  \nCFTC          2014       84\nFDIC        502224   131607\nFHFA         22188     2754\nOCC        1473861  1987120\nSEC         316561    44974"
                        ],
                        "orientation": "v",
                        "type": "bar",
                        "uid": "56a51697-9792-49e8-9325-6082ae5f9e85",
                        "x": [
                            "Debit Card",
                            "Deposit Account"
                        ],
                        "y": [
                            223,
                            493
                        ]
                    }
                ],
                "_js2py_restyle": {},
                "_js2py_update": {},
                "_last_layout_edit_id": 1,
                "_layout": {
                    "autosize": true,
                    "barmode": "group",
                    "hovermode": "closest",
                    "template": {},
                    "title": {
                        "text": "SAR Filings by State and Product"
                    }
                },
                "_model_module_version": "0.9.1",
                "_py2js_addTraces": {},
                "_py2js_animate": {},
                "_py2js_deleteTraces": {},
                "_py2js_moveTraces": {},
                "_py2js_removeLayoutProps": {},
                "_py2js_removeTraceProps": {},
                "_py2js_restyle": {},
                "_py2js_update": {},
                "_view_count": 0,
                "_view_module_version": "0.9.1"
            }
        },
        "a4975d72fbcc48c19525665154608ef0": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "2014",
                    "2019",
                    "2015",
                    "2018",
                    "2017",
                    "2016",
                    "2012",
                    "2013"
                ],
                "description": "Date : ",
                "index": 1,
                "layout": "IPY_MODEL_dc470433634749e5bed6931fc587dea4",
                "style": "IPY_MODEL_7ad11631f3734f5198f7742419b79b7e"
            }
        },
        "a4a68558d14640d9b2867889ac24d6ab": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "a558b8c097c74ec89d9c1ecd27d0eb32": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "a581144434934f3fa01d830747f9a037": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "a59ff9fdf8ba4d629a57ffa7f5e0ace5": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "a5b46011109140dc91867bbc149e579e": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "2014",
                    "2019",
                    "2015",
                    "2018",
                    "2017",
                    "2016",
                    "2012",
                    "2013"
                ],
                "description": "Date : ",
                "index": 1,
                "layout": "IPY_MODEL_2b0a3519844f4654b5506eab9de40513",
                "style": "IPY_MODEL_0099551ae1a34d73aead39a1c06baee1"
            }
        },
        "a5d8a11035d24eea91308782aca88123": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "2014",
                    "2019",
                    "2015",
                    "2018",
                    "2017",
                    "2016",
                    "2012",
                    "2013"
                ],
                "description": "Date : ",
                "index": 1,
                "layout": "IPY_MODEL_f35fd72a3fbd475d960845800b355f2e",
                "style": "IPY_MODEL_80d0c96e2bb04f798361489163f6a4a6"
            }
        },
        "a5f7a4374be7442ab4e11502809ca125": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "OCC",
                    "FDIC",
                    "SEC",
                    "FHFA",
                    "CFTC"
                ],
                "description": "Regulator :",
                "index": 0,
                "layout": "IPY_MODEL_e74e5e2843754ae8b4c6286439563e21",
                "style": "IPY_MODEL_76fe8c8d60464fac9eb0d1ce84ea48fd"
            }
        },
        "a5fe07d8d9a14aeba82ab14efdd27121": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "a61bb716b4d04eceb46c3f89ee81f6b9": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "a63fd57cea674e4984eb320d260178f1": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "2014",
                    "2019",
                    "2015",
                    "2018",
                    "2017",
                    "2016",
                    "2012",
                    "2013"
                ],
                "description": "Date : ",
                "index": 1,
                "layout": "IPY_MODEL_19fc15bb00de4d73a374ce7eb2a7facc",
                "style": "IPY_MODEL_66850175307c487f90ca464d951b5ad4"
            }
        },
        "a67732a11b5240e1bfe33bff0ef219f6": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "a6868e0f72b34bc9859b8a287e7dc27f": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_48d77198104e43879e0bf758f5df852f"
                ],
                "layout": "IPY_MODEL_4810aeb74b1a43cab93c9309dd200424"
            }
        },
        "a798758e4e874d83b98cba167ab69b22": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_416926855ab44d64a9269afbb0df257c"
                ],
                "layout": "IPY_MODEL_00fb68967f224c329f306100bab324ce"
            }
        },
        "a798f4078c794cdd8830148d401bf134": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "a7bc2cca9c4e404990ed3b3a4f8fd4e2": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "a7c14ec3678a4783ab6554785f964820": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "a7cd1a48897741db8cdad1e686c5583e": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "a82699936d864eeb9bac4ec257ddab1a": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "a8514570523a434a91cd20f369633186": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "2014",
                    "2019",
                    "2015",
                    "2018",
                    "2017",
                    "2016",
                    "2012",
                    "2013"
                ],
                "description": "Date : ",
                "index": 1,
                "layout": "IPY_MODEL_b7ebea5bd27341cba241fc19f49428ae",
                "style": "IPY_MODEL_f83c7c5075444caab0c21d859aee6516"
            }
        },
        "a89299d078364542b3926e1bb23890d1": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "a8b78f7ebae94220b66f077f9a089113": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "a8b880e36790437a86552f4c3b79c5de": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_a5b46011109140dc91867bbc149e579e"
                ],
                "layout": "IPY_MODEL_3998c82e4cb448898f5db1b861d80c01"
            }
        },
        "a8c3ebade4d5412bb82fd6656a9f3c32": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "2014",
                    "2019",
                    "2015",
                    "2018",
                    "2017",
                    "2016",
                    "2012",
                    "2013"
                ],
                "description": "Date : ",
                "index": 1,
                "layout": "IPY_MODEL_a0b959b83c894d6c9eba1c7ffe6b84d1",
                "style": "IPY_MODEL_bdb19e2d4bc94e87ae2ea19b7765eb73"
            }
        },
        "a8d9c65215434aacb3c8015636bdc47a": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "a926c95d8cb048cea27b76c329c1413e": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "a965610b88c74cbeb6146cbf0a91140f": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "a970ed306b7c49c3bc0e26e1bc576e28": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "a9e4828947ee4becaaa9a2b2226dcbc3": {
            "model_name": "FigureModel",
            "model_module": "plotlywidget",
            "model_module_version": "0.9.1",
            "state": {
                "_config": {
                    "plotlyServerURL": "https://plot.ly"
                },
                "_data": [
                    {
                        "marker": {
                            "color": "rgb(26, 118, 255)",
                            "line": {
                                "color": "rgba(100, 10, 205, 1.0)",
                                "width": 2
                            }
                        },
                        "orientation": "v",
                        "type": "bar",
                        "uid": "d4d30f45-e58b-42fb-8e6d-1d55e95ab39a",
                        "x": [
                            "Debit Card",
                            "Deposit Account"
                        ],
                        "y": [
                            223,
                            493
                        ]
                    }
                ],
                "_js2py_restyle": {},
                "_js2py_update": {},
                "_last_layout_edit_id": 3,
                "_last_trace_edit_id": 2,
                "_layout": {
                    "annotations": [
                        {
                            "font": {
                                "color": "red",
                                "size": 10
                            },
                            "showarrow": false,
                            "text": "Source: FINCEN.gov",
                            "x": 1,
                            "xanchor": "right",
                            "xref": "paper",
                            "xshift": 0,
                            "y": -0.15,
                            "yanchor": "auto",
                            "yref": "paper",
                            "yshift": 0
                        }
                    ],
                    "autosize": true,
                    "barmode": "group",
                    "hovermode": "closest",
                    "template": {},
                    "title": {
                        "text": "SAR Filings by State and Product"
                    },
                    "xaxis": {
                        "title": {
                            "text": "SARs Filing Type"
                        }
                    },
                    "yaxis": {
                        "title": {
                            "text": "Number of Filings"
                        }
                    }
                },
                "_model_module_version": "0.9.1",
                "_py2js_addTraces": {},
                "_py2js_animate": {},
                "_py2js_deleteTraces": {},
                "_py2js_moveTraces": {},
                "_py2js_removeLayoutProps": {},
                "_py2js_removeTraceProps": {},
                "_py2js_restyle": {},
                "_view_count": 0,
                "_view_module_version": "0.9.1"
            }
        },
        "aa02ce9037cf4ba7a1f2fda215165325": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "aa0ab65719664c54a4d0d4b8ebfdafdc": {
            "model_name": "FigureModel",
            "model_module": "plotlywidget",
            "model_module_version": "0.9.1",
            "state": {
                "_config": {
                    "plotlyServerURL": "https://plot.ly"
                },
                "_data": [
                    {
                        "marker": {
                            "color": "rgb(26, 118, 255)",
                            "line": {
                                "color": "rgba(100, 10, 205, 1.0)",
                                "width": 2
                            }
                        },
                        "orientation": "v",
                        "type": "bar",
                        "uid": "818f1ff4-6376-4838-a92d-af57fe51838f",
                        "x": [
                            "Debit Card",
                            "Deposit Account"
                        ],
                        "y": [
                            223,
                            493
                        ]
                    }
                ],
                "_js2py_restyle": {},
                "_js2py_update": {},
                "_last_layout_edit_id": 1,
                "_layout": {
                    "annotations": [
                        {
                            "font": {
                                "color": "red",
                                "size": 10
                            },
                            "showarrow": false,
                            "text": "Source: FINCEN.gov",
                            "x": 1,
                            "xanchor": "right",
                            "xref": "paper",
                            "xshift": 0,
                            "y": -0.15,
                            "yanchor": "auto",
                            "yref": "paper",
                            "yshift": 0
                        }
                    ],
                    "autosize": true,
                    "barmode": "group",
                    "hovermode": "closest",
                    "plot_bgcolor": "light grey",
                    "template": {},
                    "title": {
                        "text": "SAR Filings by State and Product"
                    }
                },
                "_model_module_version": "0.9.1",
                "_py2js_addTraces": {},
                "_py2js_animate": {},
                "_py2js_deleteTraces": {},
                "_py2js_moveTraces": {},
                "_py2js_removeLayoutProps": {},
                "_py2js_removeTraceProps": {},
                "_py2js_restyle": {},
                "_py2js_update": {},
                "_view_count": 0,
                "_view_module_version": "0.9.1"
            }
        },
        "aa0b55def2ca4faa9304868585e43701": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_a5d8a11035d24eea91308782aca88123"
                ],
                "layout": "IPY_MODEL_395e5f72be924356871df049f2bfd4b9"
            }
        },
        "aa1eb2cb55c644788ea2c123ac094d58": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "aa329f450d7b4f7191363a97c1f19878": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "aa8b8f5b4653425292e04e6b702a3933": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "aab5cae53ffd4d58a20512fd4fb2b3c0": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "2014",
                    "2019",
                    "2015",
                    "2018",
                    "2017",
                    "2016",
                    "2012",
                    "2013"
                ],
                "description": "Date : ",
                "index": 1,
                "layout": "IPY_MODEL_3fc51500c714461bbde743bdd289df4d",
                "style": "IPY_MODEL_12068c9f595347deb0c3e31dcfed9d81"
            }
        },
        "ab0f14a782494957a96781621fb776e5": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "Alabama",
                    "Arizona",
                    "Arkansas",
                    "California",
                    "Colorado",
                    "Connecticut",
                    "Delaware",
                    "District of Columbia",
                    "Florida",
                    "Georgia",
                    "Hawaii",
                    "Idaho",
                    "Illinois",
                    "Indiana",
                    "Iowa",
                    "Kansas",
                    "Kentucky",
                    "Louisiana",
                    "Maine",
                    "Maryland",
                    "Massachusetts",
                    "Michigan",
                    "Minnesota",
                    "Mississippi",
                    "Missouri",
                    "Montana",
                    "Nebraska",
                    "Nevada",
                    "New Hampshire",
                    "New Jersey",
                    "New Mexico",
                    "New York",
                    "North Carolina",
                    "North Dakota",
                    "Ohio",
                    "Oklahoma",
                    "Oregon",
                    "Pennsylvania",
                    "Puerto Rico",
                    "Rhode Island",
                    "South Carolina",
                    "South Dakota",
                    "Tennessee",
                    "Texas",
                    "Utah",
                    "Vermont",
                    "Virginia",
                    "Washington",
                    "West Virginia",
                    "Wisconsin"
                ],
                "description": "Filing State :",
                "index": 0,
                "layout": "IPY_MODEL_3af5398c371e494ca549bf12714176bc",
                "style": "IPY_MODEL_34826e38e7e9468b8ab2e75fa19cae12"
            }
        },
        "ab2066d0c65247808ea4725f17e76bc6": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "ab326676bfee40aba5bbef345929f3bf": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "ab61c32050c54e01afae00ba811d72b5": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "ab64245eb4b64626adbdb65a8813d1c6": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "abdacac19ba14cc0914369b421468672": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_c510d07c50d34ca58825724b59fb436a",
                    "IPY_MODEL_fad41783c5514c979d4542433bb21097"
                ],
                "layout": "IPY_MODEL_83e2d4ff74f5402bbc1dcc3f29b3ebac"
            }
        },
        "ac51356fc07b4529984b6d504160ceb4": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "Alabama",
                    "Arizona",
                    "Arkansas",
                    "California",
                    "Colorado",
                    "Connecticut",
                    "Delaware",
                    "District of Columbia",
                    "Florida",
                    "Georgia",
                    "Hawaii",
                    "Idaho",
                    "Illinois",
                    "Indiana",
                    "Iowa",
                    "Kansas",
                    "Kentucky",
                    "Louisiana",
                    "Maine",
                    "Maryland",
                    "Massachusetts",
                    "Michigan",
                    "Minnesota",
                    "Mississippi",
                    "Missouri",
                    "Montana",
                    "Nebraska",
                    "Nevada",
                    "New Hampshire",
                    "New Jersey",
                    "New Mexico",
                    "New York",
                    "North Carolina",
                    "North Dakota",
                    "Ohio",
                    "Oklahoma",
                    "Oregon",
                    "Pennsylvania",
                    "Puerto Rico",
                    "Rhode Island",
                    "South Carolina",
                    "South Dakota",
                    "Tennessee",
                    "Texas",
                    "Utah",
                    "Vermont",
                    "Virginia",
                    "Washington",
                    "West Virginia",
                    "Wisconsin"
                ],
                "description": "Filing State :",
                "index": 0,
                "layout": "IPY_MODEL_f156dc531d744b0d91d940d8b55a6fe9",
                "style": "IPY_MODEL_45f48e9594074e4c807b9bf2199ad38d"
            }
        },
        "ac7b2a3bf249489698b89fede6da4be8": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "ac7f0b361a70435e97c59f0e496048a3": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_f0d6b9daf03647a5b461ba1a94f8bf00"
                ],
                "layout": "IPY_MODEL_3ddfdee0c5ed438eb7cc4660b3f156a7"
            }
        },
        "ac806ab9064545d3adc396ac486cf154": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "ac890c2f7af54efe8d3693b9e459c944": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "Alabama",
                    "Arizona",
                    "Arkansas",
                    "California",
                    "Colorado",
                    "Connecticut",
                    "Delaware",
                    "District of Columbia",
                    "Florida",
                    "Georgia",
                    "Hawaii",
                    "Idaho",
                    "Illinois",
                    "Indiana",
                    "Iowa",
                    "Kansas",
                    "Kentucky",
                    "Louisiana",
                    "Maine",
                    "Maryland",
                    "Massachusetts",
                    "Michigan",
                    "Minnesota",
                    "Mississippi",
                    "Missouri",
                    "Montana",
                    "Nebraska",
                    "Nevada",
                    "New Hampshire",
                    "New Jersey",
                    "New Mexico",
                    "New York",
                    "North Carolina",
                    "North Dakota",
                    "Ohio",
                    "Oklahoma",
                    "Oregon",
                    "Pennsylvania",
                    "Puerto Rico",
                    "Rhode Island",
                    "South Carolina",
                    "South Dakota",
                    "Tennessee",
                    "Texas",
                    "Utah",
                    "Vermont",
                    "Virginia",
                    "Washington",
                    "West Virginia",
                    "Wisconsin"
                ],
                "description": "Filing State :",
                "index": 0,
                "layout": "IPY_MODEL_7bdd732d0ea04c9db16c88f5b28aae58",
                "style": "IPY_MODEL_369c031861bf468cb31146311ae67a58"
            }
        },
        "acb48b3a8cf14642af426106239ed09f": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "acd1a0a7dc514f7290c62090a86b4b59": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_07a86387e3a54a1cae4b0e9fdb7c7582"
                ],
                "layout": "IPY_MODEL_04436bbc1b184d22ab0440826ec590f4"
            }
        },
        "ad1d127b106143dfa18a48f792a30411": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "Alabama",
                    "Arizona",
                    "Arkansas",
                    "California",
                    "Colorado",
                    "Connecticut",
                    "Delaware",
                    "District of Columbia",
                    "Florida",
                    "Georgia",
                    "Hawaii",
                    "Idaho",
                    "Illinois",
                    "Indiana",
                    "Iowa",
                    "Kansas",
                    "Kentucky",
                    "Louisiana",
                    "Maine",
                    "Maryland",
                    "Massachusetts",
                    "Michigan",
                    "Minnesota",
                    "Mississippi",
                    "Missouri",
                    "Montana",
                    "Nebraska",
                    "Nevada",
                    "New Hampshire",
                    "New Jersey",
                    "New Mexico",
                    "New York",
                    "North Carolina",
                    "North Dakota",
                    "Ohio",
                    "Oklahoma",
                    "Oregon",
                    "Pennsylvania",
                    "Puerto Rico",
                    "Rhode Island",
                    "South Carolina",
                    "South Dakota",
                    "Tennessee",
                    "Texas",
                    "Utah",
                    "Vermont",
                    "Virginia",
                    "Washington",
                    "West Virginia",
                    "Wisconsin"
                ],
                "description": "Filing State :",
                "index": 0,
                "layout": "IPY_MODEL_9ac536a125f1416c90490c2d5a42d949",
                "style": "IPY_MODEL_120d9d0e290048369a2fb154b6b569d8"
            }
        },
        "ad288b22ecde43dba5be5716f78ddacb": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "adb19d9897ae4f94be212c27d08fb72e": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "adfbd8d1f18f40a9b77e6f7b1c7875cb": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "ae244d7ee6e94bc5935daebfc7c90abd": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "ae336d20844d4b519e83dd51fff8780c": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "ae415173e77d4f898a3b350c3635c87c": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "2014",
                    "2019",
                    "2015",
                    "2018",
                    "2017",
                    "2016",
                    "2012",
                    "2013"
                ],
                "description": "Date : ",
                "index": 1,
                "layout": "IPY_MODEL_d5af5829adb242f9a154b7dde185a472",
                "style": "IPY_MODEL_550cada29adf4f289d981fdcee335ff7"
            }
        },
        "ae45610d16634b78a1a9808c3c71afe1": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "Alabama",
                    "Arizona",
                    "Arkansas",
                    "California",
                    "Colorado",
                    "Connecticut",
                    "Delaware",
                    "District of Columbia",
                    "Florida",
                    "Georgia",
                    "Hawaii",
                    "Idaho",
                    "Illinois",
                    "Indiana",
                    "Iowa",
                    "Kansas",
                    "Kentucky",
                    "Louisiana",
                    "Maine",
                    "Maryland",
                    "Massachusetts",
                    "Michigan",
                    "Minnesota",
                    "Mississippi",
                    "Missouri",
                    "Montana",
                    "Nebraska",
                    "Nevada",
                    "New Hampshire",
                    "New Jersey",
                    "New Mexico",
                    "New York",
                    "North Carolina",
                    "North Dakota",
                    "Ohio",
                    "Oklahoma",
                    "Oregon",
                    "Pennsylvania",
                    "Puerto Rico",
                    "Rhode Island",
                    "South Carolina",
                    "South Dakota",
                    "Tennessee",
                    "Texas",
                    "Utah",
                    "Vermont",
                    "Virginia",
                    "Washington",
                    "West Virginia",
                    "Wisconsin"
                ],
                "description": "Filing State :",
                "index": 0,
                "layout": "IPY_MODEL_7ab397e3fd334cd2905c794021e85465",
                "style": "IPY_MODEL_f651f59a59754849a6860b9a0c1c2b7e"
            }
        },
        "ae5c3f354b824a7d82752c0e20953a6c": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "ae71c2e4b30845a9a2d285169a1b4e56": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "2014",
                    "2019",
                    "2015",
                    "2018",
                    "2017",
                    "2016",
                    "2012",
                    "2013"
                ],
                "description": "Date : ",
                "index": 1,
                "layout": "IPY_MODEL_9d610417f92947a78bb73786ffe518c5",
                "style": "IPY_MODEL_7bd78f4a32f9482b90796ccd8f0b5ca9"
            }
        },
        "ae760c3dc5b7415b9bb5ae254adf6a59": {
            "model_name": "FigureModel",
            "model_module": "plotlywidget",
            "model_module_version": "0.9.1",
            "state": {
                "_config": {
                    "plotlyServerURL": "https://plot.ly"
                },
                "_data": [
                    {
                        "hovertext": [
                            "                           Year   Count\nRegulator State                        \nCFTC      New York         2014      84\nFDIC      Alabama          2019     331\n          Arizona          2019     186\n          Arkansas         2019     560\n          California      40331    8778\n          Colorado         2019     712\n          Connecticut      4037     886\n          Delaware        34273   48336\n          Florida         20162    2728\n          Georgia         18149    3055\n          Hawaii           2019     650\n          Idaho            2019     175\n          Illinois        14122    2393\n          Indiana          8074    1344\n          Iowa            14122    1573\n          Kansas           4037     493\n          Kentucky         4037     691\n          Louisiana        8074    2440\n          Maine            2019     577\n          Maryland         8068     561\n          Massachusetts   14122    3640\n          Michigan         4037     476\n          Minnesota        4037     498\n          Mississippi     12107    2325\n          Missouri        16130    1739\n          Montana          2019     324\n          Nebraska        12099    2237\n          Nevada          16131    4792\n          New Hampshire    2019     176\n          New Jersey      14122    2451\n...                         ...     ...\nOCC       Ohio            56448  147585\n          Oklahoma        32255   10561\n          Oregon          34274   10734\n          Pennsylvania    46373   43569\n          Rhode Island    20167    6637\n          South Carolina  18149    9694\n          South Dakota    34282   70376\n          Tennessee       28228   12507\n          Texas           62497  119148\n          Utah            30248   26738\n          Vermont          2019     142\n          Virginia        36288  208722\n          Washington      34274   21786\n          West Virginia   12104    1305\n          Wisconsin       32259    8247\nSEC       Arizona          6047     373\n          California      28235    3240\n          Colorado        14104    1728\n          Connecticut     14122    2093\n          Florida         16135     938\n          Massachusetts   42342    6075\n          Nebraska        26215    2830\n          New Jersey      22178    1663\n          New York        32262    5769\n          Pennsylvania    16130    3075\n          Rhode Island    36297    5476\n          Texas           22187    1428\n          Utah            10076    8051\n          Virginia        14115    1269\n          Washington      16116     966\n\n[117 rows x 2 columns]"
                        ],
                        "orientation": "v",
                        "type": "bar",
                        "uid": "89c3aa7b-d831-406e-9632-172758dfed20",
                        "x": [
                            "Debit Card",
                            "Deposit Account"
                        ],
                        "y": [
                            223,
                            493
                        ]
                    }
                ],
                "_js2py_restyle": {},
                "_js2py_update": {},
                "_last_layout_edit_id": 1,
                "_layout": {
                    "autosize": true,
                    "barmode": "group",
                    "hovermode": "closest",
                    "template": {},
                    "title": {
                        "text": "SAR Filings by State and Product"
                    }
                },
                "_model_module_version": "0.9.1",
                "_py2js_addTraces": {},
                "_py2js_animate": {},
                "_py2js_deleteTraces": {},
                "_py2js_moveTraces": {},
                "_py2js_removeLayoutProps": {},
                "_py2js_removeTraceProps": {},
                "_py2js_restyle": {},
                "_py2js_update": {},
                "_view_count": 0,
                "_view_module_version": "0.9.1"
            }
        },
        "ae7ce221844b41a5936cd214b1e9c9d7": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_b556bc64f4ca4d4d87b9bae93cbc7296"
                ],
                "layout": "IPY_MODEL_5b2fb93d154043549b746e16b65e5bab"
            }
        },
        "aea3c87a4a1e4260b10b831ef12a899a": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "OCC",
                    "FDIC",
                    "SEC",
                    "FHFA",
                    "CFTC"
                ],
                "description": "Regulator :",
                "index": 0,
                "layout": "IPY_MODEL_ba80c8144bf54394affec26570aafa4f",
                "style": "IPY_MODEL_67868449c24d46fc87af7eb699809576"
            }
        },
        "aefc795e279a4d13b305d3d03e6532c7": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_7a27c5674541460e94aa7ffa48a426d5"
                ],
                "layout": "IPY_MODEL_ca8acc775cc84d82b03792dfc605955e"
            }
        },
        "af41d7e3fe4e46efbbc44f0d84bee51e": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "2014",
                    "2019",
                    "2015",
                    "2018",
                    "2017",
                    "2016",
                    "2012",
                    "2013"
                ],
                "description": "Date : ",
                "index": 1,
                "layout": "IPY_MODEL_eebdc3d5a0dd446db4b3a19b98ad459d",
                "style": "IPY_MODEL_405d62cb020d4e828d67c7775e130826"
            }
        },
        "af8880007a204006bdbad33daafb080f": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "afefaaced26848be89f8e16386b4f934": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "aff77e94fd2b433ab00d6deab61a7df4": {
            "model_name": "VBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_e1d3f92bcb17485e90035958241f286f",
                    "IPY_MODEL_625b5bce455842d6b971c0650edd6819",
                    "IPY_MODEL_f9d073d15ea54a42881600e0e0fd5cd8"
                ],
                "layout": "IPY_MODEL_8b8bd823c3684f3392dbd6d2268325c8"
            }
        },
        "b00a39b35b6c4adf8872face38883668": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "b01ad2e904fc459394e1241799449419": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "b01c47f5a65d406081fd11b2a67f98c3": {
            "model_name": "FigureModel",
            "model_module": "plotlywidget",
            "model_module_version": "0.9.1",
            "state": {
                "_config": {
                    "plotlyServerURL": "https://plot.ly"
                },
                "_data": [
                    {
                        "orientation": "v",
                        "text": "y",
                        "textposition": "auto",
                        "type": "bar",
                        "uid": "b0db801e-6766-4e56-be82-7254eb96a3ac",
                        "x": [
                            "Debit Card",
                            "Deposit Account"
                        ],
                        "y": [
                            223,
                            493
                        ]
                    }
                ],
                "_js2py_restyle": {},
                "_js2py_update": {},
                "_last_layout_edit_id": 1,
                "_layout": {
                    "annotations": [
                        {
                            "font": {
                                "color": "red",
                                "size": 10
                            },
                            "showarrow": false,
                            "text": "Source: FINCEN.gov",
                            "x": 1,
                            "xanchor": "right",
                            "xref": "paper",
                            "xshift": 0,
                            "y": -0.15,
                            "yanchor": "auto",
                            "yref": "paper",
                            "yshift": 0
                        }
                    ],
                    "autosize": true,
                    "barmode": "group",
                    "hovermode": "closest",
                    "template": {},
                    "title": {
                        "text": "SAR Filings by State and Product"
                    }
                },
                "_model_module_version": "0.9.1",
                "_py2js_addTraces": {},
                "_py2js_animate": {},
                "_py2js_deleteTraces": {},
                "_py2js_moveTraces": {},
                "_py2js_removeLayoutProps": {},
                "_py2js_removeTraceProps": {},
                "_py2js_restyle": {},
                "_py2js_update": {},
                "_view_count": 0,
                "_view_module_version": "0.9.1"
            }
        },
        "b02378bdd98c435dbbae96c84734af0e": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_5a402ecb91054695ba2446f8611b1ee8",
                    "IPY_MODEL_f3fde8875fd7415ea2892a9f20d06402"
                ],
                "layout": "IPY_MODEL_2ed0dd38d9914fc6921e1ad23459708b"
            }
        },
        "b03c1cc3e85d45c5adf51191509131ae": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "OCC",
                    "FDIC",
                    "SEC",
                    "FHFA",
                    "CFTC"
                ],
                "description": "Regulator :",
                "index": 0,
                "layout": "IPY_MODEL_ceb072fc9d01409b9786e2cc0a484ec2",
                "style": "IPY_MODEL_6e218126c2a6499e854aa07b9ef9fbb2"
            }
        },
        "b04fa3242e4d42b7bd815910fc2eaf3f": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "b068e6a3b5154693b44e7d0452cd40c1": {
            "model_name": "FigureModel",
            "model_module": "plotlywidget",
            "model_module_version": "0.9.1",
            "state": {
                "_config": {
                    "plotlyServerURL": "https://plot.ly"
                },
                "_data": [
                    {
                        "orientation": "v",
                        "type": "bar",
                        "uid": "82e3bce6-2d4c-4073-af3e-ca7ced886b96",
                        "x": [
                            "Debit Card",
                            "Deposit Account"
                        ],
                        "y": [
                            223,
                            493
                        ]
                    }
                ],
                "_js2py_restyle": {},
                "_js2py_update": {},
                "_last_layout_edit_id": 3,
                "_last_trace_edit_id": 2,
                "_layout": {
                    "autosize": true,
                    "barmode": "group",
                    "hovermode": "closest",
                    "template": {},
                    "title": {
                        "text": "SAR Filings by State and Product"
                    },
                    "xaxis": {
                        "title": {
                            "text": "SARs Filing Type"
                        }
                    },
                    "yaxis": {
                        "title": {
                            "text": "Number of Filings"
                        }
                    }
                },
                "_model_module_version": "0.9.1",
                "_py2js_addTraces": {},
                "_py2js_animate": {},
                "_py2js_deleteTraces": {},
                "_py2js_moveTraces": {},
                "_py2js_removeLayoutProps": {},
                "_py2js_removeTraceProps": {},
                "_py2js_restyle": {},
                "_view_count": 0,
                "_view_module_version": "0.9.1"
            }
        },
        "b0e38bfaf7294ea7b0e758da26bf0a0f": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "b0ea8f61d60e4b9ba467f9a1808a3f92": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "OCC",
                    "FDIC",
                    "SEC",
                    "FHFA",
                    "CFTC"
                ],
                "description": "Regulator :",
                "index": 0,
                "layout": "IPY_MODEL_d11dc17938084f5286ee77b12b531289",
                "style": "IPY_MODEL_30c99b1f595d4d66acf4d44f153e24ec"
            }
        },
        "b14ad5306ac94d728db91cbbd9a80a89": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "b19fe5257f014b34b2abc4a2d4d23ae4": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "b1d0b300a1bf48849d30fa28c6dcc543": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "2014",
                    "2019",
                    "2015",
                    "2018",
                    "2017",
                    "2016",
                    "2012",
                    "2013"
                ],
                "description": "Date : ",
                "index": 1,
                "layout": "IPY_MODEL_f7b07034dd394a04857e6ef5f9eb971e",
                "style": "IPY_MODEL_854bb9f9672549fd8c889f3cc079e01d"
            }
        },
        "b1e336fd3b7c4d9a84148dc17ff232be": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "OCC",
                    "FDIC",
                    "SEC",
                    "FHFA",
                    "CFTC"
                ],
                "description": "Regulator :",
                "index": 0,
                "layout": "IPY_MODEL_4bb0b80c3b8948298947792638b0b10c",
                "style": "IPY_MODEL_1d128f6f386d4f89b61d1a2890b4ae33"
            }
        },
        "b23a802453034ab3a5c6262e1cb70f87": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_a8514570523a434a91cd20f369633186"
                ],
                "layout": "IPY_MODEL_53b314f6578045ffa7fc65a403d5faf5"
            }
        },
        "b27f89a4c1754a69898067ad66dd542d": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_5450c342522b4c96b38139bbbada1a34"
                ],
                "layout": "IPY_MODEL_9b8e81eb229641c3815a91538d116081"
            }
        },
        "b2ade52b17724facb03a81738bb2519b": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "b3152bc095ca4ea6b2de7f6b59f6a9b9": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "b34f2e428ee74e7c80178ced24374e51": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "OCC",
                    "FDIC",
                    "SEC",
                    "FHFA",
                    "CFTC"
                ],
                "description": "Regulator :",
                "index": 0,
                "layout": "IPY_MODEL_1815b04cae2541359ca2e69a71a74b08",
                "style": "IPY_MODEL_9e37205cafd941be8b6def825bc04ce2"
            }
        },
        "b3f7064867af4ffdb58f66ceb01fe61a": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "b4487b948a414e39b8f86548fb568305": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "b44e9cd95a494e6791bcfcb68d29c6ed": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "OCC",
                    "FDIC",
                    "SEC",
                    "FHFA",
                    "CFTC"
                ],
                "description": "Regulator :",
                "index": 0,
                "layout": "IPY_MODEL_cd2a2b3fe37d4071bb9992eb4228a000",
                "style": "IPY_MODEL_4f4f9b3946ef4343ad7fe5a2dd9d6b1f"
            }
        },
        "b4563c486cd6465cb8fd61352fdfa1a4": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "OCC",
                    "FDIC",
                    "SEC",
                    "FHFA",
                    "CFTC"
                ],
                "description": "Regulator :",
                "index": 0,
                "layout": "IPY_MODEL_322f18565d2a4a9182c27174ac842d9a",
                "style": "IPY_MODEL_f2e516c18cee4ad29466b97f7e7ee8f3"
            }
        },
        "b485a0539a68494c84711c872724848d": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "b4fb4491b9c245178979d9b6bce95abe": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "b51fe10f6cc344ffad709c0ae0569d06": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "b534edca07914fe6b307ca1f09c08d18": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "b556bc64f4ca4d4d87b9bae93cbc7296": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "2014",
                    "2019",
                    "2015",
                    "2018",
                    "2017",
                    "2016",
                    "2012",
                    "2013"
                ],
                "description": "Date : ",
                "index": 1,
                "layout": "IPY_MODEL_c371587c4a224f35b9fb9abcd6310aab",
                "style": "IPY_MODEL_bb2d36ff959c45fabaf435641553691a"
            }
        },
        "b55c8a7311704627b5c3a66ed801d16e": {
            "model_name": "VBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_91b85afbc3454ef79e18b3f6507c69e5",
                    "IPY_MODEL_b7ced92d56e44b42beb3e713e0a62423",
                    "IPY_MODEL_1f3e4a24f81842f2935d483df7166cb6"
                ],
                "layout": "IPY_MODEL_983f5588cf744e899318026abb479ae2"
            }
        },
        "b5d9ea9608224144b5fbdddfbf2cba5d": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "b61106304b2849649ef957ecb499d790": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "b623594e6f704746810dfb86ea58f627": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "Alabama",
                    "Arizona",
                    "Arkansas",
                    "California",
                    "Colorado",
                    "Connecticut",
                    "Delaware",
                    "District of Columbia",
                    "Florida",
                    "Georgia",
                    "Hawaii",
                    "Idaho",
                    "Illinois",
                    "Indiana",
                    "Iowa",
                    "Kansas",
                    "Kentucky",
                    "Louisiana",
                    "Maine",
                    "Maryland",
                    "Massachusetts",
                    "Michigan",
                    "Minnesota",
                    "Mississippi",
                    "Missouri",
                    "Montana",
                    "Nebraska",
                    "Nevada",
                    "New Hampshire",
                    "New Jersey",
                    "New Mexico",
                    "New York",
                    "North Carolina",
                    "North Dakota",
                    "Ohio",
                    "Oklahoma",
                    "Oregon",
                    "Pennsylvania",
                    "Puerto Rico",
                    "Rhode Island",
                    "South Carolina",
                    "South Dakota",
                    "Tennessee",
                    "Texas",
                    "Utah",
                    "Vermont",
                    "Virginia",
                    "Washington",
                    "West Virginia",
                    "Wisconsin"
                ],
                "description": "Filing State :",
                "index": 0,
                "layout": "IPY_MODEL_1ea48e77a21c4c52ad94643779487907",
                "style": "IPY_MODEL_c0b940b7ea3e482ea1a1b2f29c184ad6"
            }
        },
        "b6360c3ccac24843a86ce5b6a4919671": {
            "model_name": "VBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_903202039225482e9e7606de498ffbb7",
                    "IPY_MODEL_a1036af429a143769e17c0c72bdd3154",
                    "IPY_MODEL_32b117dd596d4bacbccbef917b5576e6"
                ],
                "layout": "IPY_MODEL_bb69447bf39e4cd2b327c90f7d60e17a"
            }
        },
        "b696cb325e8f4becb59f2100f3ca5ccf": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "2014",
                    "2019",
                    "2015",
                    "2018",
                    "2017",
                    "2016",
                    "2012",
                    "2013"
                ],
                "description": "Date : ",
                "index": 1,
                "layout": "IPY_MODEL_acb48b3a8cf14642af426106239ed09f",
                "style": "IPY_MODEL_1686b63f1da442d89d8727577d0342d2"
            }
        },
        "b6a3e85cd10145feadb1f85e47281248": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "b6a68e5f5e574a85b9e4d9642f60b709": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "b6abcff35c1645d19d78c186b1ca019c": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "b6bbac5394304b74ae9e2a9415e620c7": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "2014",
                    "2019",
                    "2015",
                    "2018",
                    "2017",
                    "2016",
                    "2012",
                    "2013"
                ],
                "description": "Date : ",
                "index": 1,
                "layout": "IPY_MODEL_0f304f11b2514d69b5ca2b5cd73e5862",
                "style": "IPY_MODEL_ab61c32050c54e01afae00ba811d72b5"
            }
        },
        "b6d25c5801a648d1bf0edce30619b4f2": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "b6d7c5ead7604824a5a71420a9c5afd9": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "b6f792601b1f4c4db3f400e5e07c0273": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "OCC",
                    "FDIC",
                    "SEC",
                    "FHFA",
                    "CFTC"
                ],
                "description": "Regulator :",
                "index": 0,
                "layout": "IPY_MODEL_9f6f97b700d243828e8918addf493f52",
                "style": "IPY_MODEL_9d4444b76bdf44b68f3273ab518608f0"
            }
        },
        "b70eb3cc0e7b403c95731ead580e4f61": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_737fcc07a0184a71b4c3fd1d1d4a1a52"
                ],
                "layout": "IPY_MODEL_5349a640dc41425ea6a06332c4930831"
            }
        },
        "b718fd86d346419780fcfe07f55a4f36": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "b73830e5c0b049949b6d2e2dd7770bc9": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_3c5b91a928894f9294c87fd91ecb1b7b"
                ],
                "layout": "IPY_MODEL_17a812e43cef433783459ae473ce4019"
            }
        },
        "b73f1ce3ff4e4b94b479541873c906e2": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_f8b8e340a57c41659ae345d0bf11dc07",
                    "IPY_MODEL_1593f5bb557b4732b76ce000ee1e0072"
                ],
                "layout": "IPY_MODEL_70e1a35a3188493a83fa09e59e3d8dec"
            }
        },
        "b7adadc5fad74dc981e7203b46e69ed1": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "Alabama",
                    "Arizona",
                    "Arkansas",
                    "California",
                    "Colorado",
                    "Connecticut",
                    "Delaware",
                    "District of Columbia",
                    "Florida",
                    "Georgia",
                    "Hawaii",
                    "Idaho",
                    "Illinois",
                    "Indiana",
                    "Iowa",
                    "Kansas",
                    "Kentucky",
                    "Louisiana",
                    "Maine",
                    "Maryland",
                    "Massachusetts",
                    "Michigan",
                    "Minnesota",
                    "Mississippi",
                    "Missouri",
                    "Montana",
                    "Nebraska",
                    "Nevada",
                    "New Hampshire",
                    "New Jersey",
                    "New Mexico",
                    "New York",
                    "North Carolina",
                    "North Dakota",
                    "Ohio",
                    "Oklahoma",
                    "Oregon",
                    "Pennsylvania",
                    "Puerto Rico",
                    "Rhode Island",
                    "South Carolina",
                    "South Dakota",
                    "Tennessee",
                    "Texas",
                    "Utah",
                    "Vermont",
                    "Virginia",
                    "Washington",
                    "West Virginia",
                    "Wisconsin"
                ],
                "description": "Filing State :",
                "index": 0,
                "layout": "IPY_MODEL_419884c76d274d89a6ac82593ba28527",
                "style": "IPY_MODEL_119289f9d05e4e15b0ade113b08b7979"
            }
        },
        "b7ced92d56e44b42beb3e713e0a62423": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_d0051447fe46428e8c7b07247e8797f9",
                    "IPY_MODEL_4da74ad1f4bb459c90fbe7f9ae580754"
                ],
                "layout": "IPY_MODEL_8344b97967dc4a659ca216f17811426f"
            }
        },
        "b7ebea5bd27341cba241fc19f49428ae": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "b81db207f9a04509aa4c2beda3eb994f": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "b85c39b2849041498606a2136c27eabe": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "b862d214bae644b59a7821ea260a5255": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "b86e4fd124f54a0890ce4f92273cb6b8": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "2014",
                    "2019",
                    "2015",
                    "2018",
                    "2017",
                    "2016",
                    "2012",
                    "2013"
                ],
                "description": "Date : ",
                "index": 1,
                "layout": "IPY_MODEL_88cfc98c7b6444a0a279728075a52d31",
                "style": "IPY_MODEL_05c9d9d301d245fcb752e20819eb473c"
            }
        },
        "b893f2fda6ec456a8bea1cb4944755cc": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "b934b9fba80b4c858be3db6b0e4c3e5b": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "b98cb6367cb74a1899db9020b4267596": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "b9da9e2c6d1940fbbfb2f3ba69e894ea": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "b9e6752fa833451ab693966964bda937": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "b9f6083f94c84281ab8df453c44f0ecd": {
            "model_name": "VBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_9be1525cbc5f4c2b8f71feb8f0425e81",
                    "IPY_MODEL_c723b9deca0d4719886f094ec629ae48",
                    "IPY_MODEL_e9b484c027774f859d98ab22ba0ecee3"
                ],
                "layout": "IPY_MODEL_40e88970e4274adf8b9f8f70724f77b8"
            }
        },
        "ba0aaa81960d48e8a9e149e5fbdebbc1": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "ba10594bb4d144dab3a4159f6ece265c": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "ba1bc6d5b73f478c98c208f54004d104": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "OCC",
                    "FDIC",
                    "SEC",
                    "FHFA",
                    "CFTC"
                ],
                "description": "Regulator :",
                "index": 0,
                "layout": "IPY_MODEL_cc13ed98a9fe4166b8dc670095d27c92",
                "style": "IPY_MODEL_c3068205c45242f1bb7f080ad795ca94"
            }
        },
        "ba28eaacb00540c290df4bd86b09e787": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "Alabama",
                    "Arizona",
                    "Arkansas",
                    "California",
                    "Colorado",
                    "Connecticut",
                    "Delaware",
                    "District of Columbia",
                    "Florida",
                    "Georgia",
                    "Hawaii",
                    "Idaho",
                    "Illinois",
                    "Indiana",
                    "Iowa",
                    "Kansas",
                    "Kentucky",
                    "Louisiana",
                    "Maine",
                    "Maryland",
                    "Massachusetts",
                    "Michigan",
                    "Minnesota",
                    "Mississippi",
                    "Missouri",
                    "Montana",
                    "Nebraska",
                    "Nevada",
                    "New Hampshire",
                    "New Jersey",
                    "New Mexico",
                    "New York",
                    "North Carolina",
                    "North Dakota",
                    "Ohio",
                    "Oklahoma",
                    "Oregon",
                    "Pennsylvania",
                    "Puerto Rico",
                    "Rhode Island",
                    "South Carolina",
                    "South Dakota",
                    "Tennessee",
                    "Texas",
                    "Utah",
                    "Vermont",
                    "Virginia",
                    "Washington",
                    "West Virginia",
                    "Wisconsin"
                ],
                "description": "Filing State :",
                "index": 0,
                "layout": "IPY_MODEL_15073740281942699c0635c349476035",
                "style": "IPY_MODEL_2ed9e3ee349a4817a37d51003dc04605"
            }
        },
        "ba4c0d252e834f22befaab7249f65ef6": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "ba5071afac914b6397296793e77ccbe5": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "ba57371a22004a818b5fa643069ef1da": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "2014",
                    "2019",
                    "2015",
                    "2018",
                    "2017",
                    "2016",
                    "2012",
                    "2013"
                ],
                "description": "Date : ",
                "index": 1,
                "layout": "IPY_MODEL_0bdcbfbee39c484fbd36bd50b990c693",
                "style": "IPY_MODEL_b6d7c5ead7604824a5a71420a9c5afd9"
            }
        },
        "ba80c8144bf54394affec26570aafa4f": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "bab4621820694459bff601dfb26f1ace": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "bab5b26a07534e6298296501f59a79dd": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "bac43357dd3d4d0eb041a18588d30bad": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "bb2d36ff959c45fabaf435641553691a": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "bb6666a020c0462d94c17d48e774cddd": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "bb69447bf39e4cd2b327c90f7d60e17a": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "bb6fe6834dfd47bc8905cd99daa04fa6": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "bb7c79f95892453d9a5eb01dfa174c42": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "bbbe1a19623f425a904f72dbfadfdf63": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_d1ea8b07918948a1b5f48aced7e8e606",
                    "IPY_MODEL_34bf250be06242638e6b9d2f423e1233"
                ],
                "layout": "IPY_MODEL_e41395ee557948a6a8387fd35ca292c1"
            }
        },
        "bc6e404665924593aa819d1a23b6f494": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "bc81ec7d8d4c4234902e17db7f9fc08f": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "bcd2bf09c1b545788a95f7f0401ef463": {
            "model_name": "VBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_818be46be5b640858d00388ef068dc9c",
                    "IPY_MODEL_0b25ee1d8b394e83af443d04b7a8235b",
                    "IPY_MODEL_a4645835e3de488f860e1bc734fb0cd4"
                ],
                "layout": "IPY_MODEL_c76f0ed9d7c04ed7b409d87833a062a9"
            }
        },
        "bcd78aac7bc1425ba118464395e29f15": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "bcdaeeca947b4e79910bd1dcc01afcd1": {
            "model_name": "FigureModel",
            "model_module": "plotlywidget",
            "model_module_version": "0.9.1",
            "state": {
                "_config": {
                    "plotlyServerURL": "https://plot.ly"
                },
                "_data": [
                    {
                        "marker": {
                            "color": "rgb(26, 118, 255)",
                            "line": {
                                "color": "rgba(50, 118, 255, 1.0)",
                                "width": 2
                            }
                        },
                        "orientation": "v",
                        "type": "bar",
                        "uid": "838b5207-0357-4312-ae18-f56792ea88a8",
                        "x": [
                            "Debit Card",
                            "Deposit Account"
                        ],
                        "y": [
                            223,
                            493
                        ]
                    }
                ],
                "_js2py_restyle": {},
                "_js2py_update": {},
                "_last_layout_edit_id": 1,
                "_layout": {
                    "annotations": [
                        {
                            "font": {
                                "color": "red",
                                "size": 10
                            },
                            "showarrow": false,
                            "text": "Source: FINCEN.gov",
                            "x": 1,
                            "xanchor": "right",
                            "xref": "paper",
                            "xshift": 0,
                            "y": -0.15,
                            "yanchor": "auto",
                            "yref": "paper",
                            "yshift": 0
                        }
                    ],
                    "autosize": true,
                    "barmode": "group",
                    "hovermode": "closest",
                    "template": {},
                    "title": {
                        "text": "SAR Filings by State and Product"
                    }
                },
                "_model_module_version": "0.9.1",
                "_py2js_addTraces": {},
                "_py2js_animate": {},
                "_py2js_deleteTraces": {},
                "_py2js_moveTraces": {},
                "_py2js_removeLayoutProps": {},
                "_py2js_removeTraceProps": {},
                "_py2js_restyle": {},
                "_py2js_update": {},
                "_view_count": 0,
                "_view_module_version": "0.9.1"
            }
        },
        "bd08f8e2ce6849b3a95abbe678547bd8": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "Alabama",
                    "Arizona",
                    "Arkansas",
                    "California",
                    "Colorado",
                    "Connecticut",
                    "Delaware",
                    "District of Columbia",
                    "Florida",
                    "Georgia",
                    "Hawaii",
                    "Idaho",
                    "Illinois",
                    "Indiana",
                    "Iowa",
                    "Kansas",
                    "Kentucky",
                    "Louisiana",
                    "Maine",
                    "Maryland",
                    "Massachusetts",
                    "Michigan",
                    "Minnesota",
                    "Mississippi",
                    "Missouri",
                    "Montana",
                    "Nebraska",
                    "Nevada",
                    "New Hampshire",
                    "New Jersey",
                    "New Mexico",
                    "New York",
                    "North Carolina",
                    "North Dakota",
                    "Ohio",
                    "Oklahoma",
                    "Oregon",
                    "Pennsylvania",
                    "Puerto Rico",
                    "Rhode Island",
                    "South Carolina",
                    "South Dakota",
                    "Tennessee",
                    "Texas",
                    "Utah",
                    "Vermont",
                    "Virginia",
                    "Washington",
                    "West Virginia",
                    "Wisconsin"
                ],
                "description": "Filing State :",
                "index": 0,
                "layout": "IPY_MODEL_009131b7555f4bf7975d3dd68ab5a2d0",
                "style": "IPY_MODEL_fb469ce9fad241a585ad9f9c51130bcd"
            }
        },
        "bd909a72ae944eb0be91a12551388f9c": {
            "model_name": "VBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_caa506e482134bf9a85c18a10ac539e5",
                    "IPY_MODEL_f29b7db0f3f343b3b4bcf8c3c6314b31",
                    "IPY_MODEL_501da97b7786431d943044184290df29"
                ],
                "layout": "IPY_MODEL_7662b22548364d6c9fee9f926041ddbd"
            }
        },
        "bdb19e2d4bc94e87ae2ea19b7765eb73": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "bdbb1db9b54345e0b4528e79b20f8a09": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "Alabama",
                    "Arizona",
                    "Arkansas",
                    "California",
                    "Colorado",
                    "Connecticut",
                    "Delaware",
                    "District of Columbia",
                    "Florida",
                    "Georgia",
                    "Hawaii",
                    "Idaho",
                    "Illinois",
                    "Indiana",
                    "Iowa",
                    "Kansas",
                    "Kentucky",
                    "Louisiana",
                    "Maine",
                    "Maryland",
                    "Massachusetts",
                    "Michigan",
                    "Minnesota",
                    "Mississippi",
                    "Missouri",
                    "Montana",
                    "Nebraska",
                    "Nevada",
                    "New Hampshire",
                    "New Jersey",
                    "New Mexico",
                    "New York",
                    "North Carolina",
                    "North Dakota",
                    "Ohio",
                    "Oklahoma",
                    "Oregon",
                    "Pennsylvania",
                    "Puerto Rico",
                    "Rhode Island",
                    "South Carolina",
                    "South Dakota",
                    "Tennessee",
                    "Texas",
                    "Utah",
                    "Vermont",
                    "Virginia",
                    "Washington",
                    "West Virginia",
                    "Wisconsin"
                ],
                "description": "Filing State :",
                "index": 0,
                "layout": "IPY_MODEL_8ce15539b2a1476bae38d1982e1d0bbd",
                "style": "IPY_MODEL_003ed765ba904837a7d2d3c902c4585f"
            }
        },
        "bdbc6ff5ea2b4091925d72c367a470b3": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "be529f39366c4a4f9efc2b0f0121ba1f": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "bf03736aa23f4ec5bd9261ef0975339b": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "OCC",
                    "FDIC",
                    "SEC",
                    "FHFA",
                    "CFTC"
                ],
                "description": "Regulator :",
                "index": 0,
                "layout": "IPY_MODEL_03daae0cfbd746e0812917dae1e78cae",
                "style": "IPY_MODEL_890ab4dff6064d608769a6484bb03ffa"
            }
        },
        "bf177b6a538342389dbb838d6171e04d": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "bf78859c2c0647889a0922895f4ad8e2": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "bf9fb43f939145f587ebdb998e53caa2": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "2014",
                    "2019",
                    "2015",
                    "2018",
                    "2017",
                    "2016",
                    "2012",
                    "2013"
                ],
                "description": "Date : ",
                "index": 1,
                "layout": "IPY_MODEL_ea13c9d4a199491e9b6fa33dd3b7fc71",
                "style": "IPY_MODEL_303b89e1de984de68ec48d59896adc37"
            }
        },
        "bfcccff3260e4abab90c89b25f3694bf": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "bfff78cc6b224d1da64d2ae1067d5a26": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "c01533267352417bbe6e407e0cb8fd1a": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "c0b255ba4b344325a96559462df9a731": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "c0b940b7ea3e482ea1a1b2f29c184ad6": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "c147a9a5a3474ebc923306484925b93f": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "c14d83ecaf6c426a814c15e68b63b381": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "c161561c92b641468a731c5b000383c0": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "OCC",
                    "FDIC",
                    "SEC",
                    "FHFA",
                    "CFTC"
                ],
                "description": "Regulator :",
                "index": 0,
                "layout": "IPY_MODEL_7c9944fd604747eb9c233f54ecf83318",
                "style": "IPY_MODEL_5896c52bca164aa387c23c91871a34b0"
            }
        },
        "c177ee20f4ec4549b057ae5c4fb2e75b": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "c1dd529f30714b718d5147456470a4f5": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "c2509a3e4bca4e5a8e21eb0e695fe236": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "c25d936d9d674f33ae44cce907b07f49": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "c269d88545504c71a778caffad26bc50": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "c3068205c45242f1bb7f080ad795ca94": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "c3084d5339f549799720745c62e6dda4": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "c353c1215cdc4b368d8b8a41ee39b566": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "c371587c4a224f35b9fb9abcd6310aab": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "c3e696ae262f4ee094564a5d41e2209a": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "c49a1dcf5fb0430686125f87e311e65c": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "c4a7b106caf24623a3c9e8d805af4e3e": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "c4bedcaaf4db4e719ce1bba6b55e06b1": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "OCC",
                    "FDIC",
                    "SEC",
                    "FHFA",
                    "CFTC"
                ],
                "description": "Regulator :",
                "index": 0,
                "layout": "IPY_MODEL_396ee1b489af4cbdae7475c5a2b5204e",
                "style": "IPY_MODEL_f22f0aceee7c44878f8ead20420dad5d"
            }
        },
        "c4cc0fb2b7a845bbb3235025ee0e2b87": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "c4fcb204e4b7469698a7bbd450f3a610": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "c510d07c50d34ca58825724b59fb436a": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "Alabama",
                    "Arizona",
                    "Arkansas",
                    "California",
                    "Colorado",
                    "Connecticut",
                    "Delaware",
                    "District of Columbia",
                    "Florida",
                    "Georgia",
                    "Hawaii",
                    "Idaho",
                    "Illinois",
                    "Indiana",
                    "Iowa",
                    "Kansas",
                    "Kentucky",
                    "Louisiana",
                    "Maine",
                    "Maryland",
                    "Massachusetts",
                    "Michigan",
                    "Minnesota",
                    "Mississippi",
                    "Missouri",
                    "Montana",
                    "Nebraska",
                    "Nevada",
                    "New Hampshire",
                    "New Jersey",
                    "New Mexico",
                    "New York",
                    "North Carolina",
                    "North Dakota",
                    "Ohio",
                    "Oklahoma",
                    "Oregon",
                    "Pennsylvania",
                    "Puerto Rico",
                    "Rhode Island",
                    "South Carolina",
                    "South Dakota",
                    "Tennessee",
                    "Texas",
                    "Utah",
                    "Vermont",
                    "Virginia",
                    "Washington",
                    "West Virginia",
                    "Wisconsin"
                ],
                "description": "Filing State :",
                "index": 0,
                "layout": "IPY_MODEL_4e3178bca183453e869e559eed7b8b70",
                "style": "IPY_MODEL_2b245b11cf4846bcaa2992c858ca3c95"
            }
        },
        "c5ce78f208d1441d9a96b2442f20a4f2": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "OCC",
                    "FDIC",
                    "SEC",
                    "FHFA",
                    "CFTC"
                ],
                "description": "Regulator :",
                "index": 0,
                "layout": "IPY_MODEL_fcf27945358a43d49433b3dd8d90557e",
                "style": "IPY_MODEL_d38f589d193440f9a8c1c140cbf164e7"
            }
        },
        "c5db09dac31046be8d51b6db49fd2525": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "c5e92242f0ee4506b4a8344498c054cd": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "2014",
                    "2019",
                    "2015",
                    "2018",
                    "2017",
                    "2016",
                    "2012",
                    "2013"
                ],
                "description": "Date : ",
                "index": 1,
                "layout": "IPY_MODEL_5ee0773020814c4f9a5000f86157e991",
                "style": "IPY_MODEL_cf65fe0cf2d84661a29c4c544b653bb3"
            }
        },
        "c5fbdf883e144f11be9f0ac72b144b1f": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "c6281f015fd04bada8c7156ff655c68a": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "Alabama",
                    "Arizona",
                    "Arkansas",
                    "California",
                    "Colorado",
                    "Connecticut",
                    "Delaware",
                    "District of Columbia",
                    "Florida",
                    "Georgia",
                    "Hawaii",
                    "Idaho",
                    "Illinois",
                    "Indiana",
                    "Iowa",
                    "Kansas",
                    "Kentucky",
                    "Louisiana",
                    "Maine",
                    "Maryland",
                    "Massachusetts",
                    "Michigan",
                    "Minnesota",
                    "Mississippi",
                    "Missouri",
                    "Montana",
                    "Nebraska",
                    "Nevada",
                    "New Hampshire",
                    "New Jersey",
                    "New Mexico",
                    "New York",
                    "North Carolina",
                    "North Dakota",
                    "Ohio",
                    "Oklahoma",
                    "Oregon",
                    "Pennsylvania",
                    "Puerto Rico",
                    "Rhode Island",
                    "South Carolina",
                    "South Dakota",
                    "Tennessee",
                    "Texas",
                    "Utah",
                    "Vermont",
                    "Virginia",
                    "Washington",
                    "West Virginia",
                    "Wisconsin"
                ],
                "description": "Filing State :",
                "index": 0,
                "layout": "IPY_MODEL_14edc24df1774b44985cbc07886f9e8f",
                "style": "IPY_MODEL_f93134a8f06f48e68f42be94db95a995"
            }
        },
        "c6627040d973404bbe39015e6856e30b": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "c67f0e335c8e4cc6afd9e9c15f08bc74": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "c689aa261a374bac9172dbadb3663b78": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "c6cf91d0d43845ae8add2411b02467dd": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "c7178376c27e491d8373fa6e16ba34dd": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_fd35fb1dce334da4807462261ea0513f",
                    "IPY_MODEL_055a884974684d4baba6294cdf332605"
                ],
                "layout": "IPY_MODEL_50056a32545b46aaa80eb712e52f31bf"
            }
        },
        "c723b9deca0d4719886f094ec629ae48": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_7a6318b811a444be94b48d0867cacf21",
                    "IPY_MODEL_542aebaad7204111af810b48979b29d6"
                ],
                "layout": "IPY_MODEL_579644e5188e4ab2b8d7a6696eb9c03a"
            }
        },
        "c76f0ed9d7c04ed7b409d87833a062a9": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "c77e21ceb0cd4ec4be55966dc37d9472": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "c795b0a64558421d806e39e68f7ca100": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "c7a2507b63134c05a92c22df5af1bb55": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "c7d9e2376e96474eba7d5a3568023838": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "OCC",
                    "FDIC",
                    "SEC",
                    "FHFA",
                    "CFTC"
                ],
                "description": "Regulator :",
                "index": 0,
                "layout": "IPY_MODEL_487ee3a70bef40f8996896d2769e7dfa",
                "style": "IPY_MODEL_64075ff0953f40bc9d05eb1569116850"
            }
        },
        "c82087fc12424540b57f304a57677bd0": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "c859537ff8734426892fce93e64c9fa2": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "OCC",
                    "FDIC",
                    "SEC",
                    "FHFA",
                    "CFTC"
                ],
                "description": "Regulator :",
                "index": 0,
                "layout": "IPY_MODEL_34a6bf1c7eba46c7bed601b6f9fb9663",
                "style": "IPY_MODEL_e95a5ed842d24ae38703afc8df19c9fd"
            }
        },
        "c861404dd41c4f67aa731210a88a42fc": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "c884d136faf04e2984c208a08be67333": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "c8dfb3779ecb4d3e98dbb417f1c27d3b": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "c934f157dc6f405da141ec5109345ff0": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "2014",
                    "2019",
                    "2015",
                    "2018",
                    "2017",
                    "2016",
                    "2012",
                    "2013"
                ],
                "description": "Date : ",
                "index": 1,
                "layout": "IPY_MODEL_13f2910d9cdb4d1daadac8dd6ed2a28c",
                "style": "IPY_MODEL_3704572d8582420c889dff4a67547155"
            }
        },
        "c949278fbec54e659792e59dd76b9ad4": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_a4975d72fbcc48c19525665154608ef0"
                ],
                "layout": "IPY_MODEL_8be82ee921fd468db7b69fd438e387e0"
            }
        },
        "c9db6fc0270e4b9ca1e0f48e02b30ca4": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "2014",
                    "2019",
                    "2015",
                    "2018",
                    "2017",
                    "2016",
                    "2012",
                    "2013"
                ],
                "description": "Date : ",
                "index": 1,
                "layout": "IPY_MODEL_069bc514931749048b2f9f6444cb7b55",
                "style": "IPY_MODEL_a82699936d864eeb9bac4ec257ddab1a"
            }
        },
        "c9fdee2009a443cc9b72511ee98fd1da": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "ca0467183cfc4f9080ce6e0ab75f1ef6": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "Alabama",
                    "Arizona",
                    "Arkansas",
                    "California",
                    "Colorado",
                    "Connecticut",
                    "Delaware",
                    "District of Columbia",
                    "Florida",
                    "Georgia",
                    "Hawaii",
                    "Idaho",
                    "Illinois",
                    "Indiana",
                    "Iowa",
                    "Kansas",
                    "Kentucky",
                    "Louisiana",
                    "Maine",
                    "Maryland",
                    "Massachusetts",
                    "Michigan",
                    "Minnesota",
                    "Mississippi",
                    "Missouri",
                    "Montana",
                    "Nebraska",
                    "Nevada",
                    "New Hampshire",
                    "New Jersey",
                    "New Mexico",
                    "New York",
                    "North Carolina",
                    "North Dakota",
                    "Ohio",
                    "Oklahoma",
                    "Oregon",
                    "Pennsylvania",
                    "Puerto Rico",
                    "Rhode Island",
                    "South Carolina",
                    "South Dakota",
                    "Tennessee",
                    "Texas",
                    "Utah",
                    "Vermont",
                    "Virginia",
                    "Washington",
                    "West Virginia",
                    "Wisconsin"
                ],
                "description": "Filing State :",
                "index": 0,
                "layout": "IPY_MODEL_646cea3bafa64cb78f6e41f2c35bfc2a",
                "style": "IPY_MODEL_53030461a936487bbc9b1766b13054a2"
            }
        },
        "ca6cad7359a34e678e6c30afe843e91e": {
            "model_name": "VBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_74a10d911cc045adb5deb5006747190a",
                    "IPY_MODEL_f0c7f6f8df2744349f0358f40e07974a",
                    "IPY_MODEL_e5ee64241613438480b88523a3f6ebe3"
                ],
                "layout": "IPY_MODEL_f2c0d9f6604c4b7b88bb19e618776077"
            }
        },
        "ca6f2268d9674960a4fefedc950ed96d": {
            "model_name": "VBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_ea683e620904457daea8c1d6dd2ee22d",
                    "IPY_MODEL_82fe6e9fe4444ef28bf16e7d5feae29e",
                    "IPY_MODEL_b068e6a3b5154693b44e7d0452cd40c1"
                ],
                "layout": "IPY_MODEL_5f52c040c07443ee88c9a9a79f49a391"
            }
        },
        "ca864943d0e74629b6bce92a22c1dcda": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "OCC",
                    "FDIC",
                    "SEC",
                    "FHFA",
                    "CFTC"
                ],
                "description": "Regulator :",
                "index": 0,
                "layout": "IPY_MODEL_bb7c79f95892453d9a5eb01dfa174c42",
                "style": "IPY_MODEL_11883eb4dacc436a9f0bc259930df6b2"
            }
        },
        "ca8acc775cc84d82b03792dfc605955e": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "caa506e482134bf9a85c18a10ac539e5": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_2f69b9b514c24db68b9ea336f9d31b0b"
                ],
                "layout": "IPY_MODEL_91aef7ee3a9144349a83df8c4e572a68"
            }
        },
        "cac446f1959744d4b8e93a62ab5664a9": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "cad7b62ab65b4b41bee4cf3303e77c38": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "cafdf0b3916a4d24afbd4aceb8dc4a08": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "cb05c50d9cf4441faa416c5c5a9f16e0": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "2014",
                    "2019",
                    "2015",
                    "2018",
                    "2017",
                    "2016",
                    "2012",
                    "2013"
                ],
                "description": "Date : ",
                "index": 1,
                "layout": "IPY_MODEL_8ef333d1c5a843bbb30f940bd344d2b9",
                "style": "IPY_MODEL_7b5f35a9a58447aebc5c1c08f84604d2"
            }
        },
        "cb51050f4a444884a8e7090ce3afd30c": {
            "model_name": "VBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_8a2d3b3899f04de7a4b94dbd6e367522",
                    "IPY_MODEL_60f4de76251845bbb1e17bea5308cff9",
                    "IPY_MODEL_2c935620ebaf4cb08953cc54ca7f4298"
                ],
                "layout": "IPY_MODEL_4b7d055de5664b3bbcdd5df7fff46e84"
            }
        },
        "cb5829ebe4814c71977ea3fbfddc6987": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "cbdadc53f0ef4c749a99f7721c935013": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "cbfdabac877f4f72a3d76d7ab91742df": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "cc13ed98a9fe4166b8dc670095d27c92": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "cc185409b4a44f3ba8cac365ac62f045": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "cc240ba5d48646eeb2066a52d5fe4585": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "cc3a2750da8a4401ab2293a85d667c4e": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "cc60d3ff7fcc41768310d4b5e0ae3dce": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "cc78def55bd54bbf89d95928b2a58d17": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "ccae98e4b26f4e2c8f091fa76e16f40c": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "ccce2dc67d3945fa96f5e23015a42087": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "cce55c15785d4b069e2190eeb45c4e54": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_132a475153ba4b1ba75418b69863679c",
                    "IPY_MODEL_eca2a72b774c4d1b942dfb1826c2d60b"
                ],
                "layout": "IPY_MODEL_ed6a4aaa79694a8f956f1fcd239c5c8f"
            }
        },
        "cd2a2b3fe37d4071bb9992eb4228a000": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "cdab4393930f4a0892d72282e0bcd5ad": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "OCC",
                    "FDIC",
                    "SEC",
                    "FHFA",
                    "CFTC"
                ],
                "description": "Regulator :",
                "index": 0,
                "layout": "IPY_MODEL_19dd831cb42948a8a6b168d9b2855bbc",
                "style": "IPY_MODEL_a7c14ec3678a4783ab6554785f964820"
            }
        },
        "cdb81e0686e943e4ad34c324250646f1": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "ce079f1b40b0498fbc78290568dd07ce": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "ce78c402853a49d0aba1af32ded00126": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "2014",
                    "2019",
                    "2015",
                    "2018",
                    "2017",
                    "2016",
                    "2012",
                    "2013"
                ],
                "description": "Date : ",
                "index": 1,
                "layout": "IPY_MODEL_7cfd2876e26f4404be60c6f32bb8c550",
                "style": "IPY_MODEL_39cea490c8d4483bb6a12b4232e10bbe"
            }
        },
        "ceb072fc9d01409b9786e2cc0a484ec2": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "cebc6309a2cb49cf93568365a8cf42bd": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "cebd8f6c29db4f13b4095609bc32912a": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "2014",
                    "2019",
                    "2015",
                    "2018",
                    "2017",
                    "2016",
                    "2012",
                    "2013"
                ],
                "description": "Date : ",
                "index": 1,
                "layout": "IPY_MODEL_fa73e5b928f14ee2afe597c62e21938e",
                "style": "IPY_MODEL_655c431ffb304e048a9185305018fe40"
            }
        },
        "cf3131e90e594962b0d9280065b8a7a7": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "cf65fe0cf2d84661a29c4c544b653bb3": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "cf6d4d360132454ab772b9ea8c454169": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "OCC",
                    "FDIC",
                    "SEC",
                    "FHFA",
                    "CFTC"
                ],
                "description": "Regulator :",
                "index": 0,
                "layout": "IPY_MODEL_a26c685822e84592b9176d3fd36c63e9",
                "style": "IPY_MODEL_cbfdabac877f4f72a3d76d7ab91742df"
            }
        },
        "cf9f9bc1d4f044e8a648bd2bebbbaef8": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "Alabama",
                    "Arizona",
                    "Arkansas",
                    "California",
                    "Colorado",
                    "Connecticut",
                    "Delaware",
                    "District of Columbia",
                    "Florida",
                    "Georgia",
                    "Hawaii",
                    "Idaho",
                    "Illinois",
                    "Indiana",
                    "Iowa",
                    "Kansas",
                    "Kentucky",
                    "Louisiana",
                    "Maine",
                    "Maryland",
                    "Massachusetts",
                    "Michigan",
                    "Minnesota",
                    "Mississippi",
                    "Missouri",
                    "Montana",
                    "Nebraska",
                    "Nevada",
                    "New Hampshire",
                    "New Jersey",
                    "New Mexico",
                    "New York",
                    "North Carolina",
                    "North Dakota",
                    "Ohio",
                    "Oklahoma",
                    "Oregon",
                    "Pennsylvania",
                    "Puerto Rico",
                    "Rhode Island",
                    "South Carolina",
                    "South Dakota",
                    "Tennessee",
                    "Texas",
                    "Utah",
                    "Vermont",
                    "Virginia",
                    "Washington",
                    "West Virginia",
                    "Wisconsin"
                ],
                "description": "Filing State :",
                "index": 0,
                "layout": "IPY_MODEL_ef76602f5999421a9e3e8d9ac007ea01",
                "style": "IPY_MODEL_3a14373c744e4317a0fee5bda4570158"
            }
        },
        "cfaf7b3ca54d4704a1847523413f8fdd": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "cfc899c0612b416886f7b35bcefde17a": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_fb98974534c34f2d80799a489285c77c"
                ],
                "layout": "IPY_MODEL_698d0fc8fa2a45bdb67ed35a221874d7"
            }
        },
        "cfee4acfaae948969089237ed9104d2b": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "d0051447fe46428e8c7b07247e8797f9": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "Alabama",
                    "Alaska",
                    "Arizona",
                    "Arkansas",
                    "California",
                    "Colorado",
                    "Connecticut",
                    "Delaware",
                    "District of Columbia",
                    "Florida",
                    "Georgia",
                    "Hawaii",
                    "Idaho",
                    "Illinois",
                    "Indiana",
                    "Iowa",
                    "Kansas",
                    "Kentucky",
                    "Louisiana",
                    "Maine",
                    "Maryland",
                    "Massachusetts",
                    "Michigan",
                    "Minnesota",
                    "Mississippi",
                    "Missouri",
                    "Montana",
                    "Nebraska",
                    "Nevada",
                    "New Hampshire",
                    "New Jersey",
                    "New Mexico",
                    "New York",
                    "North Carolina",
                    "North Dakota",
                    "Ohio",
                    "Oklahoma",
                    "Oregon",
                    "Pennsylvania",
                    "Puerto Rico",
                    "Rhode Island",
                    "South Carolina",
                    "South Dakota",
                    "Tennessee",
                    "Texas",
                    "Utah",
                    "Vermont",
                    "Virginia",
                    "Washington",
                    "West Virginia",
                    "Wisconsin",
                    "Wyoming"
                ],
                "description": "Filing State :",
                "index": 32,
                "layout": "IPY_MODEL_afefaaced26848be89f8e16386b4f934",
                "style": "IPY_MODEL_c269d88545504c71a778caffad26bc50"
            }
        },
        "d0686bec7011499d9eb716cb70300a2d": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "d0aee662ab344d329005a226688bb0e7": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "d0ce5dec552f440592834ebc78e976eb": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "d0da414cba134198a0ce9eb346d8217d": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "Alabama",
                    "Arizona",
                    "Arkansas",
                    "California",
                    "Colorado",
                    "Connecticut",
                    "Delaware",
                    "District of Columbia",
                    "Florida",
                    "Georgia",
                    "Hawaii",
                    "Idaho",
                    "Illinois",
                    "Indiana",
                    "Iowa",
                    "Kansas",
                    "Kentucky",
                    "Louisiana",
                    "Maine",
                    "Maryland",
                    "Massachusetts",
                    "Michigan",
                    "Minnesota",
                    "Mississippi",
                    "Missouri",
                    "Montana",
                    "Nebraska",
                    "Nevada",
                    "New Hampshire",
                    "New Jersey",
                    "New Mexico",
                    "New York",
                    "North Carolina",
                    "North Dakota",
                    "Ohio",
                    "Oklahoma",
                    "Oregon",
                    "Pennsylvania",
                    "Puerto Rico",
                    "Rhode Island",
                    "South Carolina",
                    "South Dakota",
                    "Tennessee",
                    "Texas",
                    "Utah",
                    "Vermont",
                    "Virginia",
                    "Washington",
                    "West Virginia",
                    "Wisconsin"
                ],
                "description": "Filing State :",
                "index": 0,
                "layout": "IPY_MODEL_9620183350574939b91f9d43f6a5b071",
                "style": "IPY_MODEL_560a98b9f51b4e38bd76be09caf14290"
            }
        },
        "d11dc17938084f5286ee77b12b531289": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "d15a770f633e403ca70ff29b06fe28a1": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_1b7f47ca0fc54470a5c9357c1289f90b",
                    "IPY_MODEL_07b45612595f46299827d78ce1d23b5a"
                ],
                "layout": "IPY_MODEL_f41a3245ee6e4e588d80160c4e9fb0a0"
            }
        },
        "d1e235c69302465ca4e9fd99552b616b": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "2014",
                    "2019",
                    "2015",
                    "2018",
                    "2017",
                    "2016",
                    "2012",
                    "2013"
                ],
                "description": "Date : ",
                "index": 1,
                "layout": "IPY_MODEL_8deec8f6dbc44001b5ee2e028e48ced1",
                "style": "IPY_MODEL_705a69602939428a9f1e0cea16fb165a"
            }
        },
        "d1ea8b07918948a1b5f48aced7e8e606": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "Alabama",
                    "Arizona",
                    "Arkansas",
                    "California",
                    "Colorado",
                    "Connecticut",
                    "Delaware",
                    "District of Columbia",
                    "Florida",
                    "Georgia",
                    "Hawaii",
                    "Idaho",
                    "Illinois",
                    "Indiana",
                    "Iowa",
                    "Kansas",
                    "Kentucky",
                    "Louisiana",
                    "Maine",
                    "Maryland",
                    "Massachusetts",
                    "Michigan",
                    "Minnesota",
                    "Mississippi",
                    "Missouri",
                    "Montana",
                    "Nebraska",
                    "Nevada",
                    "New Hampshire",
                    "New Jersey",
                    "New Mexico",
                    "New York",
                    "North Carolina",
                    "North Dakota",
                    "Ohio",
                    "Oklahoma",
                    "Oregon",
                    "Pennsylvania",
                    "Puerto Rico",
                    "Rhode Island",
                    "South Carolina",
                    "South Dakota",
                    "Tennessee",
                    "Texas",
                    "Utah",
                    "Vermont",
                    "Virginia",
                    "Washington",
                    "West Virginia",
                    "Wisconsin"
                ],
                "description": "Filing State :",
                "index": 0,
                "layout": "IPY_MODEL_dc2458ac3c104ba0ba57fd2d510e6982",
                "style": "IPY_MODEL_e29ef4967f834f4ebe28fafed6bd3b8d"
            }
        },
        "d1fa5ec7369743cba07e217244938aba": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "Alabama",
                    "Arizona",
                    "Arkansas",
                    "California",
                    "Colorado",
                    "Connecticut",
                    "Delaware",
                    "District of Columbia",
                    "Florida",
                    "Georgia",
                    "Hawaii",
                    "Idaho",
                    "Illinois",
                    "Indiana",
                    "Iowa",
                    "Kansas",
                    "Kentucky",
                    "Louisiana",
                    "Maine",
                    "Maryland",
                    "Massachusetts",
                    "Michigan",
                    "Minnesota",
                    "Mississippi",
                    "Missouri",
                    "Montana",
                    "Nebraska",
                    "Nevada",
                    "New Hampshire",
                    "New Jersey",
                    "New Mexico",
                    "New York",
                    "North Carolina",
                    "North Dakota",
                    "Ohio",
                    "Oklahoma",
                    "Oregon",
                    "Pennsylvania",
                    "Puerto Rico",
                    "Rhode Island",
                    "South Carolina",
                    "South Dakota",
                    "Tennessee",
                    "Texas",
                    "Utah",
                    "Vermont",
                    "Virginia",
                    "Washington",
                    "West Virginia",
                    "Wisconsin"
                ],
                "description": "Filing State :",
                "index": 0,
                "layout": "IPY_MODEL_99c394d8201e4f5fb5ad720aefcd7a8a",
                "style": "IPY_MODEL_e75c5bd5d7564df0b4d425b8fab1a4aa"
            }
        },
        "d21d98ea5e1e430ea42e5d34d74697b7": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "OCC",
                    "FDIC",
                    "SEC",
                    "FHFA",
                    "CFTC"
                ],
                "description": "Regulator :",
                "index": 0,
                "layout": "IPY_MODEL_4c84f06a7c63428597fea0f2f11e743a",
                "style": "IPY_MODEL_d3b127993fc246e297c5eddcf1a52ae8"
            }
        },
        "d2d768fb1a724e869540ccca4f16c6cf": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "d2dda1f653864763b18ed1708c14248e": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "2014",
                    "2019",
                    "2015",
                    "2018",
                    "2017",
                    "2016",
                    "2012",
                    "2013"
                ],
                "description": "Date : ",
                "index": 1,
                "layout": "IPY_MODEL_6d9581a36b2743b79a7f805137f810d4",
                "style": "IPY_MODEL_a3cdf5d52f4141f893a068f7db2686de"
            }
        },
        "d315c46002fc4b88b02001f9c8aa4101": {
            "model_name": "VBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_091b84c92e774dd58bdfc7f315f7af9a",
                    "IPY_MODEL_33be9aaa6fda43fab2de849440794b3d",
                    "IPY_MODEL_a1f3e500c93c467f8f1451d80ed9d5c4"
                ],
                "layout": "IPY_MODEL_03adc70976a94d9aa9df49c4222f553b"
            }
        },
        "d37e8eb56ce1417b931a0717764eacba": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_0c00b72d36ce4a81a2903d4454f7800f",
                    "IPY_MODEL_134e8ca884d64d3cac0e9ecc37cb2f39"
                ],
                "layout": "IPY_MODEL_39108128d2a54c3da22972d2a3d98477"
            }
        },
        "d38f589d193440f9a8c1c140cbf164e7": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "d3b127993fc246e297c5eddcf1a52ae8": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "d3d516aa4a554306a7c6dee14c8a50eb": {
            "model_name": "FigureModel",
            "model_module": "plotlywidget",
            "model_module_version": "0.9.1",
            "state": {
                "_config": {
                    "plotlyServerURL": "https://plot.ly"
                },
                "_data": [
                    {
                        "marker": {
                            "color": "rgb(26, 118, 255)",
                            "line": {
                                "color": "rgba(100, 10, 205, 1.0)",
                                "width": 2
                            }
                        },
                        "orientation": "v",
                        "type": "bar",
                        "uid": "baf08c2e-01e9-4c77-963a-6f8395363a28",
                        "x": [
                            "Debit Card",
                            "Deposit Account"
                        ],
                        "y": [
                            223,
                            493
                        ]
                    }
                ],
                "_js2py_pointsCallback": {},
                "_js2py_restyle": {},
                "_js2py_update": {},
                "_last_layout_edit_id": 1,
                "_layout": {
                    "annotations": [
                        {
                            "font": {
                                "color": "red",
                                "size": 10
                            },
                            "showarrow": false,
                            "text": "Source: FINCEN.gov",
                            "x": 1,
                            "xanchor": "right",
                            "xref": "paper",
                            "xshift": 0,
                            "y": -0.15,
                            "yanchor": "auto",
                            "yref": "paper",
                            "yshift": 0
                        }
                    ],
                    "autosize": true,
                    "barmode": "group",
                    "hovermode": "closest",
                    "paper_bgcolor": "whitesmoke",
                    "plot_bgcolor": "whitesmoke",
                    "shapes": [
                        {
                            "line": {
                                "color": "RoyalBlue"
                            },
                            "type": "rect",
                            "x0": 0,
                            "x1": 2,
                            "y0": 0,
                            "y1": 3
                        }
                    ],
                    "template": {},
                    "title": {
                        "text": "SAR Filings by State and Product"
                    }
                },
                "_model_module_version": "0.9.1",
                "_py2js_addTraces": {},
                "_py2js_animate": {},
                "_py2js_deleteTraces": {},
                "_py2js_moveTraces": {},
                "_py2js_removeLayoutProps": {},
                "_py2js_removeTraceProps": {},
                "_py2js_restyle": {},
                "_py2js_update": {},
                "_view_count": 0,
                "_view_module_version": "0.9.1"
            }
        },
        "d40e39dd60364db2801aa76445de4efe": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "d42251c5de794ed999c12ec8e5c0ea1f": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "Alabama",
                    "Arizona",
                    "Arkansas",
                    "California",
                    "Colorado",
                    "Connecticut",
                    "Delaware",
                    "District of Columbia",
                    "Florida",
                    "Georgia",
                    "Hawaii",
                    "Idaho",
                    "Illinois",
                    "Indiana",
                    "Iowa",
                    "Kansas",
                    "Kentucky",
                    "Louisiana",
                    "Maine",
                    "Maryland",
                    "Massachusetts",
                    "Michigan",
                    "Minnesota",
                    "Mississippi",
                    "Missouri",
                    "Montana",
                    "Nebraska",
                    "Nevada",
                    "New Hampshire",
                    "New Jersey",
                    "New Mexico",
                    "New York",
                    "North Carolina",
                    "North Dakota",
                    "Ohio",
                    "Oklahoma",
                    "Oregon",
                    "Pennsylvania",
                    "Puerto Rico",
                    "Rhode Island",
                    "South Carolina",
                    "South Dakota",
                    "Tennessee",
                    "Texas",
                    "Utah",
                    "Vermont",
                    "Virginia",
                    "Washington",
                    "West Virginia",
                    "Wisconsin"
                ],
                "description": "Filing State :",
                "index": 0,
                "layout": "IPY_MODEL_d6dd09ee0dfc49de9bd6a64e468b4337",
                "style": "IPY_MODEL_f7c197cd9a8e49eaa293aafc26d9a540"
            }
        },
        "d4281a0668d44f0cb43bdd59a7cb9228": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "OCC",
                    "FDIC",
                    "SEC",
                    "FHFA",
                    "CFTC"
                ],
                "description": "Regulator :",
                "index": 0,
                "layout": "IPY_MODEL_807ca1acee4a4d60860548908ebe2b4e",
                "style": "IPY_MODEL_eb71f417de8848f4abb1ea79edf68947"
            }
        },
        "d4eef7a128a14888a6f2ac72c94820ce": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "d4f383e047b54676828fa775cad20580": {
            "model_name": "FigureModel",
            "model_module": "plotlywidget",
            "model_module_version": "0.9.1",
            "state": {
                "_config": {
                    "plotlyServerURL": "https://plot.ly"
                },
                "_data": [
                    {
                        "marker": {
                            "color": "rgb(26, 118, 255)",
                            "line": {
                                "color": "rgba(100, 10, 205, 1.0)",
                                "width": 2
                            }
                        },
                        "orientation": "v",
                        "type": "bar",
                        "uid": "05f97f98-e3e0-4e63-8a49-25ee0952af5d",
                        "x": [
                            "Debit Card",
                            "Deposit Account"
                        ],
                        "y": [
                            223,
                            493
                        ]
                    }
                ],
                "_js2py_restyle": {},
                "_js2py_update": {},
                "_last_layout_edit_id": 1,
                "_layout": {
                    "annotations": [
                        {
                            "font": {
                                "color": "red",
                                "size": 10
                            },
                            "showarrow": false,
                            "text": "Source: FINCEN.gov",
                            "x": 1,
                            "xanchor": "right",
                            "xref": "paper",
                            "xshift": 0,
                            "y": -0.15,
                            "yanchor": "auto",
                            "yref": "paper",
                            "yshift": 0
                        }
                    ],
                    "autosize": true,
                    "barmode": "group",
                    "hovermode": "closest",
                    "paper_bgcolor": "whitesmoke",
                    "plot_bgcolor": "whitesmoke",
                    "shapes": [
                        {
                            "line": {
                                "color": "RoyalBlue"
                            },
                            "type": "rect",
                            "x0": 1,
                            "x1": 2,
                            "y0": 1,
                            "y1": 3
                        }
                    ],
                    "template": {},
                    "title": {
                        "text": "SAR Filings by State and Product"
                    }
                },
                "_model_module_version": "0.9.1",
                "_py2js_addTraces": {},
                "_py2js_animate": {},
                "_py2js_deleteTraces": {},
                "_py2js_moveTraces": {},
                "_py2js_removeLayoutProps": {},
                "_py2js_removeTraceProps": {},
                "_py2js_restyle": {},
                "_py2js_update": {},
                "_view_count": 0,
                "_view_module_version": "0.9.1"
            }
        },
        "d518aceea04b4ce0b5e3fc9d4335a21c": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "OCC",
                    "FDIC",
                    "SEC",
                    "FHFA",
                    "CFTC"
                ],
                "description": "Regulator :",
                "index": 0,
                "layout": "IPY_MODEL_2d8fdc5e196c48d9abacf7bbee2d13c2",
                "style": "IPY_MODEL_71d5f258ec574c87a4a32078a56a6d82"
            }
        },
        "d532b425d6e34324b528454c4275e2aa": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "d58fec37df884047a0ac7328d7666ebe": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "d5af5829adb242f9a154b7dde185a472": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "d612186efa2b435cbea8b05927764a13": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "Alabama",
                    "Arizona",
                    "Arkansas",
                    "California",
                    "Colorado",
                    "Connecticut",
                    "Delaware",
                    "District of Columbia",
                    "Florida",
                    "Georgia",
                    "Hawaii",
                    "Idaho",
                    "Illinois",
                    "Indiana",
                    "Iowa",
                    "Kansas",
                    "Kentucky",
                    "Louisiana",
                    "Maine",
                    "Maryland",
                    "Massachusetts",
                    "Michigan",
                    "Minnesota",
                    "Mississippi",
                    "Missouri",
                    "Montana",
                    "Nebraska",
                    "Nevada",
                    "New Hampshire",
                    "New Jersey",
                    "New Mexico",
                    "New York",
                    "North Carolina",
                    "North Dakota",
                    "Ohio",
                    "Oklahoma",
                    "Oregon",
                    "Pennsylvania",
                    "Puerto Rico",
                    "Rhode Island",
                    "South Carolina",
                    "South Dakota",
                    "Tennessee",
                    "Texas",
                    "Utah",
                    "Vermont",
                    "Virginia",
                    "Washington",
                    "West Virginia",
                    "Wisconsin"
                ],
                "description": "Filing State :",
                "index": 0,
                "layout": "IPY_MODEL_83e7492d6d3a4253bc7b4a0f123f1038",
                "style": "IPY_MODEL_85c5d82878db4e368b4b635fcc0b3993"
            }
        },
        "d6b8b6da3bfe483f80c200cd558b9032": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "d6dd09ee0dfc49de9bd6a64e468b4337": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "d7135a3e2225475c9dd01786593708f7": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "d7a5b3e15f5f4e49a8932194707eb6d1": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "d87889094a254759bee1a7ce7616c143": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "OCC",
                    "FDIC",
                    "SEC",
                    "FHFA",
                    "CFTC"
                ],
                "description": "Regulator :",
                "index": 0,
                "layout": "IPY_MODEL_545d7ae0c4a04f68b1e662fade373ebf",
                "style": "IPY_MODEL_ab64245eb4b64626adbdb65a8813d1c6"
            }
        },
        "d8ed1f1134b0449ebcdbfe9391691209": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "2014",
                    "2019",
                    "2015",
                    "2018",
                    "2017",
                    "2016",
                    "2012",
                    "2013"
                ],
                "description": "Date : ",
                "index": 1,
                "layout": "IPY_MODEL_5999c0b31d26400d99668dea147b0937",
                "style": "IPY_MODEL_4c6115c691b9400bb9b1b7e17fce2be7"
            }
        },
        "d93d8b9c8a5e43b58f75d81f2fcf2e18": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_9ee21ebd3b7d40dcbaaaedb88abd63b3"
                ],
                "layout": "IPY_MODEL_ddf9b3641fc143a8836d3014c2fbae2f"
            }
        },
        "d99f1adff64442c7b7204152ab515b24": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "d9b17eb240b247ff8faa0680a34788c5": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "d9b8324de314457ca2e338e7542f4444": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "da0f3a46959d4910b3b7309d06d393c2": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "da36f4597b854ecc886e7489bd47c105": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "da581f49010e4df9ad76ca007c29f24a": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "Alabama",
                    "Arizona",
                    "Arkansas",
                    "California",
                    "Colorado",
                    "Connecticut",
                    "Delaware",
                    "District of Columbia",
                    "Florida",
                    "Georgia",
                    "Hawaii",
                    "Idaho",
                    "Illinois",
                    "Indiana",
                    "Iowa",
                    "Kansas",
                    "Kentucky",
                    "Louisiana",
                    "Maine",
                    "Maryland",
                    "Massachusetts",
                    "Michigan",
                    "Minnesota",
                    "Mississippi",
                    "Missouri",
                    "Montana",
                    "Nebraska",
                    "Nevada",
                    "New Hampshire",
                    "New Jersey",
                    "New Mexico",
                    "New York",
                    "North Carolina",
                    "North Dakota",
                    "Ohio",
                    "Oklahoma",
                    "Oregon",
                    "Pennsylvania",
                    "Puerto Rico",
                    "Rhode Island",
                    "South Carolina",
                    "South Dakota",
                    "Tennessee",
                    "Texas",
                    "Utah",
                    "Vermont",
                    "Virginia",
                    "Washington",
                    "West Virginia",
                    "Wisconsin"
                ],
                "description": "Filing State :",
                "index": 0,
                "layout": "IPY_MODEL_9d1e31f0703346c48843aa46f223e998",
                "style": "IPY_MODEL_f416e5a916784769bc86a64196808ac8"
            }
        },
        "da8b1e38196843119e69fc9005552e09": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "dab316a998c041ed83d9e10b735e1a44": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "daf39203a2fa4307a0616aa115a6ff9c": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_9e55d3c8cc9f43c29c59268988ce903b",
                    "IPY_MODEL_8333b5c8f6a1423f881d1410d6513750"
                ],
                "layout": "IPY_MODEL_995bea200dd64f1c8efd460543a268f5"
            }
        },
        "db28fd403d9845eeb1741af9f71b9896": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "db61029692fd4b76aec82419ce012216": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "db8244c9e8944293a7f0c91ed1f261e9": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_4410e038b3b14b07b13708a1dfd5a820",
                    "IPY_MODEL_d87889094a254759bee1a7ce7616c143"
                ],
                "layout": "IPY_MODEL_7c801786fa89478caf3b00a78cd042f6"
            }
        },
        "db97d7e7684e44a4845a9b8dcbab80b4": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "dbdc47a786d5422996e4f0dd29a8dd98": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "dc1bfe45e034486596b6533a5a6e89f4": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "dc2458ac3c104ba0ba57fd2d510e6982": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "dc32ebc47a754ed6a9187db60eb2cf96": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "dc470433634749e5bed6931fc587dea4": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "dc75f7483f7044298afb3029121eebe0": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "dcc6e625b13e44029fe1f2816bed0203": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "OCC",
                    "FDIC",
                    "SEC",
                    "FHFA",
                    "CFTC"
                ],
                "description": "Regulator :",
                "index": 0,
                "layout": "IPY_MODEL_f30fad2a831a4e088896d1efb6457699",
                "style": "IPY_MODEL_05bc6ffa06a24f1fbb606afd425eae35"
            }
        },
        "dcdb8fec034c400bbfd40923f10fdc28": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_4951eba8ee004057bdcb7e35fd5ba90c"
                ],
                "layout": "IPY_MODEL_790249b865774a9baaaf57008ba7a370"
            }
        },
        "dcdfc9b6d9b84784b10407319bfa52de": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "dce04276b76b481d8aed78abf4d6b5c2": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "2014",
                    "2019",
                    "2015",
                    "2018",
                    "2017",
                    "2016",
                    "2012",
                    "2013"
                ],
                "description": "Date : ",
                "index": 1,
                "layout": "IPY_MODEL_45b7a107bfa743398dbc038f250c2d20",
                "style": "IPY_MODEL_74ae3ce45b544b558624da06216a949a"
            }
        },
        "dcf60affad1f4c50a3060f9af1e2d26c": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_fbd1d20fd26c4e8dbd806d4133d586c6",
                    "IPY_MODEL_885930e0f1094a179ce80b8b04658d9b"
                ],
                "layout": "IPY_MODEL_a220c9b90e9b4e4aa15e0b40e6c837d2"
            }
        },
        "dd599a8a21bd453c96e53cd6b02fdfd5": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_bf9fb43f939145f587ebdb998e53caa2"
                ],
                "layout": "IPY_MODEL_355d947b71534aa1bce446dad8c9e557"
            }
        },
        "dd745b119b9540eeb9bd119f7a4a7831": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "dd7b2f6901d245faa1f06d4d2cd011f6": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "ddcaf76912184b66b8bae73ff18aa338": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "2014",
                    "2019",
                    "2015",
                    "2018",
                    "2017",
                    "2016",
                    "2012",
                    "2013"
                ],
                "description": "Date : ",
                "index": 1,
                "layout": "IPY_MODEL_26ada6e0417644fb8702d8568a13e995",
                "style": "IPY_MODEL_effce9efdf934ab9a5426958f2b2a033"
            }
        },
        "ddcb946a4ba54c78b043641522437a04": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "ddf323cde11f40e7bdd2940abecdc32d": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "ddf9b3641fc143a8836d3014c2fbae2f": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "de7b7fe581374f72bdb30ac5d153a34c": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "Alabama",
                    "Arizona",
                    "Arkansas",
                    "California",
                    "Colorado",
                    "Connecticut",
                    "Delaware",
                    "District of Columbia",
                    "Florida",
                    "Georgia",
                    "Hawaii",
                    "Idaho",
                    "Illinois",
                    "Indiana",
                    "Iowa",
                    "Kansas",
                    "Kentucky",
                    "Louisiana",
                    "Maine",
                    "Maryland",
                    "Massachusetts",
                    "Michigan",
                    "Minnesota",
                    "Mississippi",
                    "Missouri",
                    "Montana",
                    "Nebraska",
                    "Nevada",
                    "New Hampshire",
                    "New Jersey",
                    "New Mexico",
                    "New York",
                    "North Carolina",
                    "North Dakota",
                    "Ohio",
                    "Oklahoma",
                    "Oregon",
                    "Pennsylvania",
                    "Puerto Rico",
                    "Rhode Island",
                    "South Carolina",
                    "South Dakota",
                    "Tennessee",
                    "Texas",
                    "Utah",
                    "Vermont",
                    "Virginia",
                    "Washington",
                    "West Virginia",
                    "Wisconsin"
                ],
                "description": "Filing State :",
                "index": 0,
                "layout": "IPY_MODEL_b534edca07914fe6b307ca1f09c08d18",
                "style": "IPY_MODEL_4a29b23d8fe74a47b98331081a5a934b"
            }
        },
        "deb98c2193d047ed9ce0260f5050c294": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "2014",
                    "2019",
                    "2015",
                    "2018",
                    "2017",
                    "2016",
                    "2012",
                    "2013"
                ],
                "description": "Date : ",
                "index": 1,
                "layout": "IPY_MODEL_c2509a3e4bca4e5a8e21eb0e695fe236",
                "style": "IPY_MODEL_f7430678863548019d14e75d61145466"
            }
        },
        "dee1e91a869e4428b3f4575010208e50": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "df0518c255ce4ac891a0c8845dccd3fc": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "df3d8c4e03a7491391dea9d8c0f1dc4e": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "df3ea7308b134c34a5749656f1bad0f8": {
            "model_name": "FigureModel",
            "model_module": "plotlywidget",
            "model_module_version": "0.9.1",
            "state": {
                "_config": {
                    "plotlyServerURL": "https://plot.ly"
                },
                "_data": [
                    {
                        "orientation": "v",
                        "type": "bar",
                        "uid": "c1f5c45d-43df-4ebc-b284-b851dd0d06c6",
                        "x": [
                            "Debit Card",
                            "Deposit Account"
                        ],
                        "y": [
                            223,
                            493
                        ]
                    }
                ],
                "_js2py_restyle": {},
                "_js2py_update": {},
                "_last_layout_edit_id": 1,
                "_layout": {
                    "annotations": [
                        {
                            "font": {
                                "color": "red",
                                "size": 10
                            },
                            "showarrow": false,
                            "text": "Source: FinCEN.",
                            "x": 1,
                            "xanchor": "right",
                            "xref": "paper",
                            "xshift": 0,
                            "y": -0.15,
                            "yanchor": "auto",
                            "yref": "paper",
                            "yshift": 0
                        }
                    ],
                    "autosize": true,
                    "barmode": "group",
                    "hovermode": "closest",
                    "template": {},
                    "title": {
                        "text": "SAR Filings by State and Product"
                    }
                },
                "_model_module_version": "0.9.1",
                "_py2js_addTraces": {},
                "_py2js_animate": {},
                "_py2js_deleteTraces": {},
                "_py2js_moveTraces": {},
                "_py2js_removeLayoutProps": {},
                "_py2js_removeTraceProps": {},
                "_py2js_restyle": {},
                "_py2js_update": {},
                "_view_count": 0,
                "_view_module_version": "0.9.1"
            }
        },
        "dfa10e528cfd46ccbb1c28e9b2bdfcc1": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "dfa1208b797c4af499da64040a1deddc": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "dfd7a686ceb645178c64c5d6cc91a3d7": {
            "model_name": "FigureModel",
            "model_module": "plotlywidget",
            "model_module_version": "0.9.1",
            "state": {
                "_config": {
                    "plotlyServerURL": "https://plot.ly"
                },
                "_data": [
                    {
                        "orientation": "v",
                        "text": {
                            "dtype": "float64",
                            "shape": [
                                2
                            ]
                        },
                        "textposition": "auto",
                        "type": "bar",
                        "uid": "c910ca33-859e-49f4-9b41-30bd8ee99eae",
                        "x": [
                            "Debit Card",
                            "Deposit Account"
                        ],
                        "y": [
                            223,
                            493
                        ]
                    }
                ],
                "_js2py_restyle": {},
                "_js2py_update": {},
                "_last_layout_edit_id": 1,
                "_layout": {
                    "annotations": [
                        {
                            "font": {
                                "color": "red",
                                "size": 10
                            },
                            "showarrow": false,
                            "text": "Source: FINCEN.gov",
                            "x": 1,
                            "xanchor": "right",
                            "xref": "paper",
                            "xshift": 0,
                            "y": -0.15,
                            "yanchor": "auto",
                            "yref": "paper",
                            "yshift": 0
                        }
                    ],
                    "autosize": true,
                    "barmode": "group",
                    "hovermode": "closest",
                    "template": {},
                    "title": {
                        "text": "SAR Filings by State and Product"
                    }
                },
                "_model_module_version": "0.9.1",
                "_py2js_addTraces": {},
                "_py2js_animate": {},
                "_py2js_deleteTraces": {},
                "_py2js_moveTraces": {},
                "_py2js_removeLayoutProps": {},
                "_py2js_removeTraceProps": {},
                "_py2js_restyle": {},
                "_py2js_update": {},
                "_view_count": 0,
                "_view_module_version": "0.9.1"
            },
            "buffers": [
                {
                    "data": "AAAAAADga0AAAAAAANB+QA==",
                    "path": [
                        "_data",
                        0,
                        "text",
                        "value"
                    ],
                    "encoding": "base64"
                }
            ]
        },
        "e0296cb3f22a4023ae3f5d28896e449a": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "e0789737760445cf9af09b36764bc194": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "e12570447d364a32ac1a68b72bab42da": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "e14bbfd71f24439d827c7f77e8d01963": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "e14be314d71c4b2b87db4eea599c53a7": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_43790e4eb2d142b9a18ae3decbe7e2d0"
                ],
                "layout": "IPY_MODEL_71d3462869a44136a22f1bf434a38867"
            }
        },
        "e1cd11e07d84402da33f5489992bdd85": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "e1d3f92bcb17485e90035958241f286f": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_c5e92242f0ee4506b4a8344498c054cd"
                ],
                "layout": "IPY_MODEL_4fe8aefbdc1747b6b09b363eecc3921e"
            }
        },
        "e21640ac1aa6407790ae75cf08e162ab": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "e22040eb03754cb7af621804a3229bb6": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "Alabama",
                    "Arizona",
                    "Arkansas",
                    "California",
                    "Colorado",
                    "Connecticut",
                    "Delaware",
                    "District of Columbia",
                    "Florida",
                    "Georgia",
                    "Hawaii",
                    "Idaho",
                    "Illinois",
                    "Indiana",
                    "Iowa",
                    "Kansas",
                    "Kentucky",
                    "Louisiana",
                    "Maine",
                    "Maryland",
                    "Massachusetts",
                    "Michigan",
                    "Minnesota",
                    "Mississippi",
                    "Missouri",
                    "Montana",
                    "Nebraska",
                    "Nevada",
                    "New Hampshire",
                    "New Jersey",
                    "New Mexico",
                    "New York",
                    "North Carolina",
                    "North Dakota",
                    "Ohio",
                    "Oklahoma",
                    "Oregon",
                    "Pennsylvania",
                    "Puerto Rico",
                    "Rhode Island",
                    "South Carolina",
                    "South Dakota",
                    "Tennessee",
                    "Texas",
                    "Utah",
                    "Vermont",
                    "Virginia",
                    "Washington",
                    "West Virginia",
                    "Wisconsin"
                ],
                "description": "Filing State :",
                "index": 0,
                "layout": "IPY_MODEL_f28f9df1cd75416bbcd61fa4271f7369",
                "style": "IPY_MODEL_63f5c49c67354e10a3e66b5008456913"
            }
        },
        "e29ef4967f834f4ebe28fafed6bd3b8d": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "e3068ce4b9e24f63b4068ceb6ab31692": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "e31da5e608f74097b4f0bf92b9350625": {
            "model_name": "VBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_8d079daa2f994f01bee4d4160809c4d2",
                    "IPY_MODEL_3dcd196670324c1ea1776ee53448ff5f",
                    "IPY_MODEL_1b5d8f28429f4e1da1dfd2f9fa9490cd"
                ],
                "layout": "IPY_MODEL_3a81b61e5feb4925b58d426db0a404e1"
            }
        },
        "e341943c42474887bfc713c70c0a8987": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "e350018b67ca42378e86bffd656cf79b": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_60a3f25018294f44ac8a3c541892f04d"
                ],
                "layout": "IPY_MODEL_77514344428e475cb8d3a2d759e75c00"
            }
        },
        "e3a1e01f6a0a4bfaae26945d091da03f": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "e3de7bbc969c4561955f6f87e2bc52ad": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "e3ee5dd782df4fa986162f8d18f94c0a": {
            "model_name": "VBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_43b74c70e6ce41bcb6f967fd5ce509c5",
                    "IPY_MODEL_998e83674b4440548bf30ce12aeea4df",
                    "IPY_MODEL_0e19c738104648dca165e98c9188a201"
                ],
                "layout": "IPY_MODEL_32bdff366dd64cf19f82055534232729"
            }
        },
        "e41395ee557948a6a8387fd35ca292c1": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "e49190719ae3415a9e68e210cc72b34e": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "e4a3b6c88de44b5d9efd621aefb35a05": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "e4dfb0e2d4a84b60b6a91fb3de4e446c": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "e529cb2fb5e945bdb5f79eca27dae8da": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "e529e5b8fc684a68b2c4ef9ffb7d7251": {
            "model_name": "FigureModel",
            "model_module": "plotlywidget",
            "model_module_version": "0.9.1",
            "state": {
                "_config": {
                    "plotlyServerURL": "https://plot.ly"
                },
                "_data": [
                    {
                        "marker": {
                            "color": "rgb(26, 118, 255)",
                            "line": {
                                "color": "rgba(100, 18, 255, 1.0)",
                                "width": 2
                            }
                        },
                        "orientation": "v",
                        "type": "bar",
                        "uid": "8d0199fb-0d84-40af-bb00-39b76b116e89",
                        "x": [
                            "Debit Card",
                            "Deposit Account"
                        ],
                        "y": [
                            223,
                            493
                        ]
                    }
                ],
                "_js2py_restyle": {},
                "_js2py_update": {},
                "_last_layout_edit_id": 1,
                "_layout": {
                    "annotations": [
                        {
                            "font": {
                                "color": "red",
                                "size": 10
                            },
                            "showarrow": false,
                            "text": "Source: FINCEN.gov",
                            "x": 1,
                            "xanchor": "right",
                            "xref": "paper",
                            "xshift": 0,
                            "y": -0.15,
                            "yanchor": "auto",
                            "yref": "paper",
                            "yshift": 0
                        }
                    ],
                    "autosize": true,
                    "barmode": "group",
                    "hovermode": "closest",
                    "template": {},
                    "title": {
                        "text": "SAR Filings by State and Product"
                    }
                },
                "_model_module_version": "0.9.1",
                "_py2js_addTraces": {},
                "_py2js_animate": {},
                "_py2js_deleteTraces": {},
                "_py2js_moveTraces": {},
                "_py2js_removeLayoutProps": {},
                "_py2js_removeTraceProps": {},
                "_py2js_restyle": {},
                "_py2js_update": {},
                "_view_count": 0,
                "_view_module_version": "0.9.1"
            }
        },
        "e53655a032c34aa3a717dbe39f07fe53": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "e542318c0e234ace9bef0c370172ab95": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "e5652cc3b2254469ab31441f8273206d": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "e5ee64241613438480b88523a3f6ebe3": {
            "model_name": "FigureModel",
            "model_module": "plotlywidget",
            "model_module_version": "0.9.1",
            "state": {
                "_config": {
                    "plotlyServerURL": "https://plot.ly"
                },
                "_data": [
                    {
                        "orientation": "v",
                        "type": "bar",
                        "uid": "8e6ee15e-4c6b-4ceb-8db4-63540b8ce678",
                        "x": [
                            "Debit Card",
                            "Deposit Account"
                        ],
                        "y": [
                            223,
                            493
                        ]
                    }
                ],
                "_js2py_restyle": {},
                "_js2py_update": {},
                "_last_layout_edit_id": 1,
                "_layout": {
                    "annotations": [
                        {
                            "font": {
                                "color": "red",
                                "size": 10
                            },
                            "showarrow": false,
                            "text": "Source: Fincen.gov.",
                            "x": 1,
                            "xanchor": "right",
                            "xref": "paper",
                            "xshift": 0,
                            "y": -0.15,
                            "yanchor": "auto",
                            "yref": "paper",
                            "yshift": 0
                        }
                    ],
                    "autosize": true,
                    "barmode": "group",
                    "hovermode": "closest",
                    "template": {},
                    "title": {
                        "text": "SAR Filings by State and Product"
                    }
                },
                "_model_module_version": "0.9.1",
                "_py2js_addTraces": {},
                "_py2js_animate": {},
                "_py2js_deleteTraces": {},
                "_py2js_moveTraces": {},
                "_py2js_removeLayoutProps": {},
                "_py2js_removeTraceProps": {},
                "_py2js_restyle": {},
                "_py2js_update": {},
                "_view_count": 0,
                "_view_module_version": "0.9.1"
            }
        },
        "e60bc613f6554c96b6435f058d7f62a7": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "e60e3366c42248b797974c752db277b3": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_897457bf3ec54a84830be0a501ae8a59",
                    "IPY_MODEL_7a6b1888b9144c52b83a8deca3fc466a"
                ],
                "layout": "IPY_MODEL_10b440af36e04762925c6cc594880b68"
            }
        },
        "e617716cb79a49588e3940b8090f5bed": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "OCC",
                    "FDIC",
                    "SEC",
                    "FHFA",
                    "CFTC"
                ],
                "description": "Regulator :",
                "index": 0,
                "layout": "IPY_MODEL_35ad72028cf74ba6a747615d04bacbbf",
                "style": "IPY_MODEL_da36f4597b854ecc886e7489bd47c105"
            }
        },
        "e66463cfe2004ff593e72f1838d29809": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "e6a2bcc3f08b4a9aaa9994ea18ca566e": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "e6b51566b3744cddb1f521711dc4e60e": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "Alabama",
                    "Arizona",
                    "Arkansas",
                    "California",
                    "Colorado",
                    "Connecticut",
                    "Delaware",
                    "District of Columbia",
                    "Florida",
                    "Georgia",
                    "Hawaii",
                    "Idaho",
                    "Illinois",
                    "Indiana",
                    "Iowa",
                    "Kansas",
                    "Kentucky",
                    "Louisiana",
                    "Maine",
                    "Maryland",
                    "Massachusetts",
                    "Michigan",
                    "Minnesota",
                    "Mississippi",
                    "Missouri",
                    "Montana",
                    "Nebraska",
                    "Nevada",
                    "New Hampshire",
                    "New Jersey",
                    "New Mexico",
                    "New York",
                    "North Carolina",
                    "North Dakota",
                    "Ohio",
                    "Oklahoma",
                    "Oregon",
                    "Pennsylvania",
                    "Puerto Rico",
                    "Rhode Island",
                    "South Carolina",
                    "South Dakota",
                    "Tennessee",
                    "Texas",
                    "Utah",
                    "Vermont",
                    "Virginia",
                    "Washington",
                    "West Virginia",
                    "Wisconsin"
                ],
                "description": "Filing State :",
                "index": 0,
                "layout": "IPY_MODEL_0809cba7295041fe96a00a52e2ab26b9",
                "style": "IPY_MODEL_3915ada25de547bf9918d043dd4faa68"
            }
        },
        "e6bbb82f8a6345b6a7ee30e51aad94ac": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "e6c51ef6db3e4c9fa64bbaf9f391cf0e": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "e6d627c94c9740869220ccf1750abbe3": {
            "model_name": "VBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_b27f89a4c1754a69898067ad66dd542d",
                    "IPY_MODEL_2748664ec0ba49e7ad566617a3688007",
                    "IPY_MODEL_1128511b3e48472fadbe33abfd1f12b5"
                ],
                "layout": "IPY_MODEL_09180af1f2124239aa6f0dd43a4d8ecd"
            }
        },
        "e70cd3dafdcb405bb5a89e63dfd2b03f": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "e74a4597027c45229f446fbf1c231a47": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_80a9b68e90304d94ac2fd9ba38609820"
                ],
                "layout": "IPY_MODEL_9fa3dd17fb554613a49c88444ac8e6f0"
            }
        },
        "e74e5a766c454282bc5387d7b5ce2545": {
            "model_name": "FigureModel",
            "model_module": "plotlywidget",
            "model_module_version": "0.9.1",
            "state": {
                "_config": {
                    "plotlyServerURL": "https://plot.ly"
                },
                "_data": [
                    {
                        "marker": {
                            "color": "rgb(26, 118, 255)",
                            "line": {
                                "color": "rgba(100, 10, 205, 1.0)",
                                "width": 2
                            }
                        },
                        "orientation": "v",
                        "type": "bar",
                        "uid": "926c397c-9552-4d4b-afec-9736a3b35560",
                        "x": [
                            "Debit Card",
                            "Deposit Account"
                        ],
                        "y": [
                            223,
                            493
                        ]
                    }
                ],
                "_js2py_restyle": {},
                "_js2py_update": {},
                "_last_layout_edit_id": 1,
                "_layout": {
                    "annotations": [
                        {
                            "font": {
                                "color": "red",
                                "size": 10
                            },
                            "showarrow": false,
                            "text": "Source: FINCEN.gov",
                            "x": 1,
                            "xanchor": "right",
                            "xref": "paper",
                            "xshift": 0,
                            "y": -0.15,
                            "yanchor": "auto",
                            "yref": "paper",
                            "yshift": 0
                        }
                    ],
                    "autosize": true,
                    "barmode": "group",
                    "hovermode": "closest",
                    "plot_bgcolor": "lightgrey",
                    "template": {},
                    "title": {
                        "text": "SAR Filings by State and Product"
                    }
                },
                "_model_module_version": "0.9.1",
                "_py2js_addTraces": {},
                "_py2js_animate": {},
                "_py2js_deleteTraces": {},
                "_py2js_moveTraces": {},
                "_py2js_removeLayoutProps": {},
                "_py2js_removeTraceProps": {},
                "_py2js_restyle": {},
                "_py2js_update": {},
                "_view_count": 0,
                "_view_module_version": "0.9.1"
            }
        },
        "e74e5e2843754ae8b4c6286439563e21": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "e74e63809fc74181aa217a56483cd8e0": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "e75c5bd5d7564df0b4d425b8fab1a4aa": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "e75ddef53ea2452a8285d88f98c7a3ab": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "e79d27b1dcd34bd4b21e81ba021bb9b1": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "2017",
                    "2015",
                    "2016",
                    "2014",
                    "2019",
                    "2018",
                    "2012",
                    "2013"
                ],
                "description": "Date : ",
                "index": 4,
                "layout": "IPY_MODEL_c5fbdf883e144f11be9f0ac72b144b1f",
                "style": "IPY_MODEL_c67f0e335c8e4cc6afd9e9c15f08bc74"
            }
        },
        "e79e4f02d509422c929d72ddca10976b": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "e7f0ac72ba1545bf93ec7e5848c92cfe": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_ddcaf76912184b66b8bae73ff18aa338"
                ],
                "layout": "IPY_MODEL_2705a0705ef94cf9b1ce0fb397b96f7b"
            }
        },
        "e8446da8801c48c6a21faf358a6a1cdd": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "e87389e598c747f9a1b6bc07370d44b4": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "e8917b02ba8a4713917ba24889a55e9c": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "e902dbd3dfc8414bb25fbc1ef618b0dd": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "e95a5ed842d24ae38703afc8df19c9fd": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "e9957da46c2049da9f87e94c02fee7d8": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "Alabama",
                    "Arizona",
                    "Arkansas",
                    "California",
                    "Colorado",
                    "Connecticut",
                    "Delaware",
                    "District of Columbia",
                    "Florida",
                    "Georgia",
                    "Hawaii",
                    "Idaho",
                    "Illinois",
                    "Indiana",
                    "Iowa",
                    "Kansas",
                    "Kentucky",
                    "Louisiana",
                    "Maine",
                    "Maryland",
                    "Massachusetts",
                    "Michigan",
                    "Minnesota",
                    "Mississippi",
                    "Missouri",
                    "Montana",
                    "Nebraska",
                    "Nevada",
                    "New Hampshire",
                    "New Jersey",
                    "New Mexico",
                    "New York",
                    "North Carolina",
                    "North Dakota",
                    "Ohio",
                    "Oklahoma",
                    "Oregon",
                    "Pennsylvania",
                    "Puerto Rico",
                    "Rhode Island",
                    "South Carolina",
                    "South Dakota",
                    "Tennessee",
                    "Texas",
                    "Utah",
                    "Vermont",
                    "Virginia",
                    "Washington",
                    "West Virginia",
                    "Wisconsin"
                ],
                "description": "Filing State :",
                "index": 0,
                "layout": "IPY_MODEL_14e24057ddd44f34800c06bdb3659a80",
                "style": "IPY_MODEL_982835a8ac334486a6371f7660ede82e"
            }
        },
        "e9b484c027774f859d98ab22ba0ecee3": {
            "model_name": "FigureModel",
            "model_module": "plotlywidget",
            "model_module_version": "0.9.1",
            "state": {
                "_config": {
                    "plotlyServerURL": "https://plot.ly"
                },
                "_data": [
                    {
                        "orientation": "v",
                        "type": "bar",
                        "uid": "004bd927-901b-4b01-8437-f8bb709c656c",
                        "x": [
                            "Debit Card",
                            "Deposit Account"
                        ],
                        "y": [
                            223,
                            493
                        ]
                    }
                ],
                "_js2py_pointsCallback": {},
                "_js2py_restyle": {},
                "_js2py_update": {},
                "_last_layout_edit_id": 1,
                "_layout": {
                    "autosize": true,
                    "barmode": "group",
                    "hovermode": "closest",
                    "template": {},
                    "title": {
                        "text": "SAR Filings by State and Product"
                    }
                },
                "_model_module_version": "0.9.1",
                "_py2js_addTraces": {},
                "_py2js_animate": {},
                "_py2js_deleteTraces": {},
                "_py2js_moveTraces": {},
                "_py2js_removeLayoutProps": {},
                "_py2js_removeTraceProps": {},
                "_py2js_restyle": {},
                "_py2js_update": {},
                "_view_count": 0,
                "_view_module_version": "0.9.1"
            }
        },
        "e9b53a816aad49e49fb6ad0990791653": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "2014",
                    "2019",
                    "2015",
                    "2018",
                    "2017",
                    "2016",
                    "2012",
                    "2013"
                ],
                "description": "Date : ",
                "index": 1,
                "layout": "IPY_MODEL_6e20abc433a04260ac246ca8087b975a",
                "style": "IPY_MODEL_f0970d7adc6445929d09a37c1e470314"
            }
        },
        "e9b93d4adaed4216a13c3c9527117eff": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_0e59c55f213047119f553986b3ef2f6a"
                ],
                "layout": "IPY_MODEL_0718b9923202492894b2cd94f88008d0"
            }
        },
        "ea13c9d4a199491e9b6fa33dd3b7fc71": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "ea2dd84a06d245a5a346f4a4d7cf6f20": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "ea33a49fb1e749f88769aaf701821531": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "ea3f983d62f84eab984359e060bdfc04": {
            "model_name": "VBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_77c41ae349144535896851f0049e269f",
                    "IPY_MODEL_ec134457dc3f406db4ec3786dc719ec9",
                    "IPY_MODEL_e74e5a766c454282bc5387d7b5ce2545"
                ],
                "layout": "IPY_MODEL_73c0ae5e7a514490ac9ea670cd48445a"
            }
        },
        "ea415e3debcf4c039f7ed46e60cd0850": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "ea683e620904457daea8c1d6dd2ee22d": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_3c8bd760910d498295175fd99775ee45"
                ],
                "layout": "IPY_MODEL_07b48e1fec1040849bc8c4b264fc60b5"
            }
        },
        "ea715a0e04fb446b8bd289f5aeae8a3f": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "ea85de7d4a4e4d68a04b9f639191d2f6": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_d0da414cba134198a0ce9eb346d8217d",
                    "IPY_MODEL_52b9680a8ab24668a73284e0063effa1"
                ],
                "layout": "IPY_MODEL_eeff515338aa4a0e846eeefcafc45597"
            }
        },
        "ead9d51d000e4f95b4f7bdc8e104f4b8": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "eb3744bdf58a4aa6ab173235bddace8a": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_d1fa5ec7369743cba07e217244938aba",
                    "IPY_MODEL_6de33d948e6f41f09d1399121faeefba"
                ],
                "layout": "IPY_MODEL_f52b17c936a0472b94c7f2a78bcc91c7"
            }
        },
        "eb47ee6067a548e4a68c07596458e7be": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "2014",
                    "2019",
                    "2015",
                    "2018",
                    "2017",
                    "2016",
                    "2012",
                    "2013"
                ],
                "description": "Date : ",
                "index": 1,
                "layout": "IPY_MODEL_f5e33b369a814c8ea8f0cb64ecbf1782",
                "style": "IPY_MODEL_ed44a7f522ba4476b0cac2ef4dcb561d"
            }
        },
        "eb68cddcce224abf8fe5c0a55f43d42c": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "eb71f417de8848f4abb1ea79edf68947": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "eb903587316d4ba58b98236a80f19d18": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "eba9cb824e9f4266af5fdf353357c402": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "ebed06ca34174517b27757643ce400b8": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "ec134457dc3f406db4ec3786dc719ec9": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_8206a6c10ee3429cbd22b542ca808ce9",
                    "IPY_MODEL_060480c31f384661997b4aed2806ff14"
                ],
                "layout": "IPY_MODEL_ce079f1b40b0498fbc78290568dd07ce"
            }
        },
        "ec622642e8b44a2f95cb7d27c348b0ff": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "OCC",
                    "FDIC",
                    "SEC",
                    "FHFA",
                    "CFTC"
                ],
                "description": "Regulator :",
                "index": 0,
                "layout": "IPY_MODEL_a30722e8eb324b07b0249b65eb43fbb2",
                "style": "IPY_MODEL_c77e21ceb0cd4ec4be55966dc37d9472"
            }
        },
        "ec86a5a837e24bd69477f0f9f172ee2b": {
            "model_name": "VBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_66521a7ae6774f2baba377d24867ff80",
                    "IPY_MODEL_dcf60affad1f4c50a3060f9af1e2d26c",
                    "IPY_MODEL_26cc4400ce924df5ab06c3e74487cc3d"
                ],
                "layout": "IPY_MODEL_9f4dab769a6b48819222133010db35d6"
            }
        },
        "eca2a72b774c4d1b942dfb1826c2d60b": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "OCC",
                    "FDIC",
                    "SEC",
                    "FHFA",
                    "CFTC"
                ],
                "description": "Regulator :",
                "index": 0,
                "layout": "IPY_MODEL_b81db207f9a04509aa4c2beda3eb994f",
                "style": "IPY_MODEL_b19fe5257f014b34b2abc4a2d4d23ae4"
            }
        },
        "ece35dcac6904ca894c81b4d6e6659b8": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "ecfe4bd536a94a03b75ece98a78ba8c3": {
            "model_name": "VBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_230dad5038fb4f909010543fc612f708",
                    "IPY_MODEL_ea85de7d4a4e4d68a04b9f639191d2f6",
                    "IPY_MODEL_8b75492536c44ef7b9aadbfb9ade9dd5"
                ],
                "layout": "IPY_MODEL_69d77fee427a42cd82efad2f817f76ae"
            }
        },
        "ed44a7f522ba4476b0cac2ef4dcb561d": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "ed47368a0d3345fd8ca4f1f8153e00e5": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "ed6a4aaa79694a8f956f1fcd239c5c8f": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "ed721a5c757a45b2a21e4395b383a96b": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "OCC",
                    "FDIC",
                    "SEC",
                    "FHFA",
                    "CFTC"
                ],
                "description": "Regulator :",
                "index": 0,
                "layout": "IPY_MODEL_a4127e03e95c4b86bf4e898688d19cd6",
                "style": "IPY_MODEL_c49a1dcf5fb0430686125f87e311e65c"
            }
        },
        "ed840ba31f224f4f9030196592a953a7": {
            "model_name": "FigureModel",
            "model_module": "plotlywidget",
            "model_module_version": "0.9.1",
            "state": {
                "_config": {
                    "plotlyServerURL": "https://plot.ly"
                },
                "_data": [
                    {
                        "marker": {
                            "color": "rgb(26, 118, 255)",
                            "line": {
                                "color": "rgba(100, 10, 205, 1.0)",
                                "width": 2
                            }
                        },
                        "orientation": "v",
                        "type": "bar",
                        "uid": "ebd00b72-1fb2-4ad6-8739-476dfafed5ad",
                        "x": [
                            "Debit Card",
                            "Deposit Account"
                        ],
                        "y": [
                            223,
                            493
                        ]
                    }
                ],
                "_js2py_restyle": {},
                "_js2py_update": {},
                "_last_layout_edit_id": 1,
                "_layout": {
                    "annotations": [
                        {
                            "font": {
                                "color": "red",
                                "size": 10
                            },
                            "showarrow": false,
                            "text": "Source: FINCEN.gov",
                            "x": 1,
                            "xanchor": "right",
                            "xref": "paper",
                            "xshift": 0,
                            "y": -0.15,
                            "yanchor": "auto",
                            "yref": "paper",
                            "yshift": 0
                        }
                    ],
                    "autosize": true,
                    "barmode": "group",
                    "hovermode": "closest",
                    "paper_bgcolor": "whitesmoke",
                    "plot_bgcolor": "whitesmoke",
                    "shapes": [
                        {
                            "line": {
                                "color": "RoyalBlue"
                            },
                            "type": "rect",
                            "x0": 1,
                            "x1": 2,
                            "y0": 1,
                            "y1": 3
                        },
                        {
                            "fillcolor": "LightSkyBlue",
                            "line": {
                                "color": "RoyalBlue",
                                "width": 2
                            },
                            "type": "rect",
                            "x0": 3,
                            "x1": 6,
                            "y0": 1,
                            "y1": 2
                        }
                    ],
                    "template": {},
                    "title": {
                        "text": "SAR Filings by State and Product"
                    }
                },
                "_model_module_version": "0.9.1",
                "_py2js_addTraces": {},
                "_py2js_animate": {},
                "_py2js_deleteTraces": {},
                "_py2js_moveTraces": {},
                "_py2js_removeLayoutProps": {},
                "_py2js_removeTraceProps": {},
                "_py2js_restyle": {},
                "_py2js_update": {},
                "_view_count": 0,
                "_view_module_version": "0.9.1"
            }
        },
        "edc63da29144455389c6bb4e581e0d24": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "Alabama",
                    "Arizona",
                    "Arkansas",
                    "California",
                    "Colorado",
                    "Connecticut",
                    "Delaware",
                    "District of Columbia",
                    "Florida",
                    "Georgia",
                    "Hawaii",
                    "Idaho",
                    "Illinois",
                    "Indiana",
                    "Iowa",
                    "Kansas",
                    "Kentucky",
                    "Louisiana",
                    "Maine",
                    "Maryland",
                    "Massachusetts",
                    "Michigan",
                    "Minnesota",
                    "Mississippi",
                    "Missouri",
                    "Montana",
                    "Nebraska",
                    "Nevada",
                    "New Hampshire",
                    "New Jersey",
                    "New Mexico",
                    "New York",
                    "North Carolina",
                    "North Dakota",
                    "Ohio",
                    "Oklahoma",
                    "Oregon",
                    "Pennsylvania",
                    "Puerto Rico",
                    "Rhode Island",
                    "South Carolina",
                    "South Dakota",
                    "Tennessee",
                    "Texas",
                    "Utah",
                    "Vermont",
                    "Virginia",
                    "Washington",
                    "West Virginia",
                    "Wisconsin"
                ],
                "description": "Filing State :",
                "index": 0,
                "layout": "IPY_MODEL_cb5829ebe4814c71977ea3fbfddc6987",
                "style": "IPY_MODEL_fbba474f96d241b49477ef4a3154a0a1"
            }
        },
        "ee0b398463d445d689b43e46b06d07c9": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "ee11b527dc7c4ed6aa968ea71ef5581d": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "eebdc3d5a0dd446db4b3a19b98ad459d": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "eec154c22c7f47399e1afad0a7029889": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "Alabama",
                    "Arizona",
                    "Arkansas",
                    "California",
                    "Colorado",
                    "Connecticut",
                    "Delaware",
                    "District of Columbia",
                    "Florida",
                    "Georgia",
                    "Hawaii",
                    "Idaho",
                    "Illinois",
                    "Indiana",
                    "Iowa",
                    "Kansas",
                    "Kentucky",
                    "Louisiana",
                    "Maine",
                    "Maryland",
                    "Massachusetts",
                    "Michigan",
                    "Minnesota",
                    "Mississippi",
                    "Missouri",
                    "Montana",
                    "Nebraska",
                    "Nevada",
                    "New Hampshire",
                    "New Jersey",
                    "New Mexico",
                    "New York",
                    "North Carolina",
                    "North Dakota",
                    "Ohio",
                    "Oklahoma",
                    "Oregon",
                    "Pennsylvania",
                    "Puerto Rico",
                    "Rhode Island",
                    "South Carolina",
                    "South Dakota",
                    "Tennessee",
                    "Texas",
                    "Utah",
                    "Vermont",
                    "Virginia",
                    "Washington",
                    "West Virginia",
                    "Wisconsin"
                ],
                "description": "Filing State :",
                "index": 0,
                "layout": "IPY_MODEL_2e8b801e39a743d8846c7e56379d9b9f",
                "style": "IPY_MODEL_9509df825a814c99986be8b4c3685c6e"
            }
        },
        "eecbd58379954402ba7537cff5c7f9d2": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "eed62db92bc24083aa25f640e90da6c9": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "eee845c0882d4ea9ad470452c9704454": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "eef75df9c75f400e88d86350c0349532": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "eeff515338aa4a0e846eeefcafc45597": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "ef347057468a4d8788bdc26ff81efd4b": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_02169c8bda3340e2af4a137e7738e66f"
                ],
                "layout": "IPY_MODEL_f811b10e912b4bc28f935ce4595cf622"
            }
        },
        "ef76602f5999421a9e3e8d9ac007ea01": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "ef94baa096a340ceab79bf6920c7b572": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "2014",
                    "2019",
                    "2015",
                    "2018",
                    "2017",
                    "2016",
                    "2012",
                    "2013"
                ],
                "description": "Date : ",
                "index": 1,
                "layout": "IPY_MODEL_9943dd49b4834195acd96f28b2d16b59",
                "style": "IPY_MODEL_d9b8324de314457ca2e338e7542f4444"
            }
        },
        "ef99b0dfdb5f4d819be5a33546431fec": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "ef9f573e259f41009a6b08cccd71babc": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "2014",
                    "2019",
                    "2015",
                    "2018",
                    "2017",
                    "2016",
                    "2012",
                    "2013"
                ],
                "description": "Date : ",
                "index": 1,
                "layout": "IPY_MODEL_a965610b88c74cbeb6146cbf0a91140f",
                "style": "IPY_MODEL_32b689e098b34b7bbf3c558375bf55f2"
            }
        },
        "effce9efdf934ab9a5426958f2b2a033": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "f08f9dff66c14e7cb2ddfe9ecffa4b52": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "OCC",
                    "FDIC",
                    "SEC",
                    "FHFA",
                    "CFTC"
                ],
                "description": "Regulator :",
                "index": 0,
                "layout": "IPY_MODEL_148bf5a2afbc4c4d9808b6f702e4963a",
                "style": "IPY_MODEL_770eec173fb445b3bd68a630620475ca"
            }
        },
        "f0970d7adc6445929d09a37c1e470314": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "f0c7f6f8df2744349f0358f40e07974a": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_2fc3edbdcc2b4cf58ee53e223f1f7435",
                    "IPY_MODEL_4b3736e4283b49b9b08b1deffc9e9acc"
                ],
                "layout": "IPY_MODEL_e542318c0e234ace9bef0c370172ab95"
            }
        },
        "f0d6b9daf03647a5b461ba1a94f8bf00": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "2014",
                    "2019",
                    "2015",
                    "2018",
                    "2017",
                    "2016",
                    "2012",
                    "2013"
                ],
                "description": "Date : ",
                "index": 1,
                "layout": "IPY_MODEL_a024c3943fbe4982b429e980a60ede7e",
                "style": "IPY_MODEL_2ee3668abfd04ab5b037bfeb078e7371"
            }
        },
        "f1381ffb58924c87910528c375f1150e": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "2014",
                    "2019",
                    "2015",
                    "2018",
                    "2017",
                    "2016",
                    "2012",
                    "2013"
                ],
                "description": "Date : ",
                "index": 1,
                "layout": "IPY_MODEL_c861404dd41c4f67aa731210a88a42fc",
                "style": "IPY_MODEL_2d4bb3e11d1a4e56a0852a38fb8c1317"
            }
        },
        "f138427d03ca4e28b9c4672a73ee07f0": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_ae415173e77d4f898a3b350c3635c87c"
                ],
                "layout": "IPY_MODEL_b9da9e2c6d1940fbbfb2f3ba69e894ea"
            }
        },
        "f1518b438ce7445dbc3b0171ae42cc6e": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "f156dc531d744b0d91d940d8b55a6fe9": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "f18bb5a7ec9f417a9e35688dfb74f9a8": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "f19697e076b249909776b97ce59e7b9e": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "f1b81fd9bd8045778faeee68d38822d0": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "f219f198e6484fd7b9b582cb176592ae": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "f22f0aceee7c44878f8ead20420dad5d": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "f28f9df1cd75416bbcd61fa4271f7369": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "f29b7db0f3f343b3b4bcf8c3c6314b31": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_1f3a907f5ccc4804b4c1f217ef8ea77f",
                    "IPY_MODEL_2052b1e2a730461a977ffdb288624d37"
                ],
                "layout": "IPY_MODEL_c4cc0fb2b7a845bbb3235025ee0e2b87"
            }
        },
        "f2c0d9f6604c4b7b88bb19e618776077": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "f2d8a68c679541df86a7ccc0e2563d67": {
            "model_name": "FigureModel",
            "model_module": "plotlywidget",
            "model_module_version": "0.9.1",
            "state": {
                "_config": {
                    "plotlyServerURL": "https://plot.ly"
                },
                "_data": [
                    {
                        "marker": {
                            "color": "rgb(26, 118, 255)"
                        },
                        "orientation": "v",
                        "type": "bar",
                        "uid": "8c7623ca-7554-46f9-96ae-0292b17d93e5",
                        "x": [
                            "Debit Card",
                            "Deposit Account"
                        ],
                        "y": [
                            223,
                            493
                        ]
                    }
                ],
                "_js2py_restyle": {},
                "_js2py_update": {},
                "_last_layout_edit_id": 1,
                "_layout": {
                    "annotations": [
                        {
                            "font": {
                                "color": "red",
                                "size": 10
                            },
                            "showarrow": false,
                            "text": "Source: FINCEN.gov",
                            "x": 1,
                            "xanchor": "right",
                            "xref": "paper",
                            "xshift": 0,
                            "y": -0.15,
                            "yanchor": "auto",
                            "yref": "paper",
                            "yshift": 0
                        }
                    ],
                    "autosize": true,
                    "barmode": "group",
                    "hovermode": "closest",
                    "template": {},
                    "title": {
                        "text": "SAR Filings by State and Product"
                    }
                },
                "_model_module_version": "0.9.1",
                "_py2js_addTraces": {},
                "_py2js_animate": {},
                "_py2js_deleteTraces": {},
                "_py2js_moveTraces": {},
                "_py2js_removeLayoutProps": {},
                "_py2js_removeTraceProps": {},
                "_py2js_restyle": {},
                "_py2js_update": {},
                "_view_count": 0,
                "_view_module_version": "0.9.1"
            }
        },
        "f2e516c18cee4ad29466b97f7e7ee8f3": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "f2f2760c656644d08be8d3030661adc9": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "f3064b0115c34f7186d69a6da85af024": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "f30fad2a831a4e088896d1efb6457699": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "f33f22da270e413b961e2674eeb8fba0": {
            "model_name": "FigureModel",
            "model_module": "plotlywidget",
            "model_module_version": "0.9.1",
            "state": {
                "_config": {
                    "plotlyServerURL": "https://plot.ly"
                },
                "_data": [
                    {
                        "marker": {
                            "color": "rgb(26, 118, 255)",
                            "line": {
                                "color": "rgba(80, 118, 255, 1.0)",
                                "width": 2
                            }
                        },
                        "orientation": "v",
                        "type": "bar",
                        "uid": "6136efcf-1c5d-4101-a161-6007b545a417",
                        "x": [
                            "Debit Card",
                            "Deposit Account"
                        ],
                        "y": [
                            223,
                            493
                        ]
                    }
                ],
                "_js2py_restyle": {},
                "_js2py_update": {},
                "_last_layout_edit_id": 1,
                "_layout": {
                    "annotations": [
                        {
                            "font": {
                                "color": "red",
                                "size": 10
                            },
                            "showarrow": false,
                            "text": "Source: FINCEN.gov",
                            "x": 1,
                            "xanchor": "right",
                            "xref": "paper",
                            "xshift": 0,
                            "y": -0.15,
                            "yanchor": "auto",
                            "yref": "paper",
                            "yshift": 0
                        }
                    ],
                    "autosize": true,
                    "barmode": "group",
                    "hovermode": "closest",
                    "template": {},
                    "title": {
                        "text": "SAR Filings by State and Product"
                    }
                },
                "_model_module_version": "0.9.1",
                "_py2js_addTraces": {},
                "_py2js_animate": {},
                "_py2js_deleteTraces": {},
                "_py2js_moveTraces": {},
                "_py2js_removeLayoutProps": {},
                "_py2js_removeTraceProps": {},
                "_py2js_restyle": {},
                "_py2js_update": {},
                "_view_count": 0,
                "_view_module_version": "0.9.1"
            }
        },
        "f35fd72a3fbd475d960845800b355f2e": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "f37de8ee492d4975961cce86b991ce53": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "f3b0dbee580640f4a4545eed89020e15": {
            "model_name": "VBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_337e40e1d834427a829fad80c113f973",
                    "IPY_MODEL_abdacac19ba14cc0914369b421468672",
                    "IPY_MODEL_aa0ab65719664c54a4d0d4b8ebfdafdc"
                ],
                "layout": "IPY_MODEL_3da1a967acad4f56ac2dd3b61f6e1754"
            }
        },
        "f3c5e825da8d4b6a80dbf655ec6da305": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "Alabama",
                    "Arizona",
                    "Arkansas",
                    "California",
                    "Colorado",
                    "Connecticut",
                    "Delaware",
                    "District of Columbia",
                    "Florida",
                    "Georgia",
                    "Hawaii",
                    "Idaho",
                    "Illinois",
                    "Indiana",
                    "Iowa",
                    "Kansas",
                    "Kentucky",
                    "Louisiana",
                    "Maine",
                    "Maryland",
                    "Massachusetts",
                    "Michigan",
                    "Minnesota",
                    "Mississippi",
                    "Missouri",
                    "Montana",
                    "Nebraska",
                    "Nevada",
                    "New Hampshire",
                    "New Jersey",
                    "New Mexico",
                    "New York",
                    "North Carolina",
                    "North Dakota",
                    "Ohio",
                    "Oklahoma",
                    "Oregon",
                    "Pennsylvania",
                    "Puerto Rico",
                    "Rhode Island",
                    "South Carolina",
                    "South Dakota",
                    "Tennessee",
                    "Texas",
                    "Utah",
                    "Vermont",
                    "Virginia",
                    "Washington",
                    "West Virginia",
                    "Wisconsin"
                ],
                "description": "Filing State :",
                "index": 0,
                "layout": "IPY_MODEL_b485a0539a68494c84711c872724848d",
                "style": "IPY_MODEL_5eae50dcd9b24a89b7418a3db031edf5"
            }
        },
        "f3e70adbcc2349ae8f2d77950544f0b7": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "f3fde8875fd7415ea2892a9f20d06402": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "OCC",
                    "FDIC",
                    "SEC",
                    "FHFA",
                    "CFTC"
                ],
                "description": "Regulator :",
                "index": 0,
                "layout": "IPY_MODEL_9d817ec4f59c4590aba8ab6c8098bcd5",
                "style": "IPY_MODEL_851952bf687845aca91a41f2e4f44af6"
            }
        },
        "f40fe97b85a74ddc905b053b5456ab7b": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "f416e5a916784769bc86a64196808ac8": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "f41a3245ee6e4e588d80160c4e9fb0a0": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "f433844b3bd245cf9a38521ec963e0ca": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "Alabama",
                    "Arizona",
                    "Arkansas",
                    "California",
                    "Colorado",
                    "Connecticut",
                    "Delaware",
                    "District of Columbia",
                    "Florida",
                    "Georgia",
                    "Hawaii",
                    "Idaho",
                    "Illinois",
                    "Indiana",
                    "Iowa",
                    "Kansas",
                    "Kentucky",
                    "Louisiana",
                    "Maine",
                    "Maryland",
                    "Massachusetts",
                    "Michigan",
                    "Minnesota",
                    "Mississippi",
                    "Missouri",
                    "Montana",
                    "Nebraska",
                    "Nevada",
                    "New Hampshire",
                    "New Jersey",
                    "New Mexico",
                    "New York",
                    "North Carolina",
                    "North Dakota",
                    "Ohio",
                    "Oklahoma",
                    "Oregon",
                    "Pennsylvania",
                    "Puerto Rico",
                    "Rhode Island",
                    "South Carolina",
                    "South Dakota",
                    "Tennessee",
                    "Texas",
                    "Utah",
                    "Vermont",
                    "Virginia",
                    "Washington",
                    "West Virginia",
                    "Wisconsin"
                ],
                "description": "Filing State :",
                "index": 0,
                "layout": "IPY_MODEL_e4dfb0e2d4a84b60b6a91fb3de4e446c",
                "style": "IPY_MODEL_92bd33e977f444f1998075c78033710a"
            }
        },
        "f4454819a3fa4d60a5a5c8e37e08917b": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "2014",
                    "2019",
                    "2015",
                    "2018",
                    "2017",
                    "2016",
                    "2012",
                    "2013"
                ],
                "description": "Date : ",
                "index": 1,
                "layout": "IPY_MODEL_46be0f6e29fb407d90d8ebfa4f24e856",
                "style": "IPY_MODEL_c884d136faf04e2984c208a08be67333"
            }
        },
        "f483ff8bda7b43b6a84c5d772c7e16dc": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "f4949ef841f94753b62b45e0cb3c1eab": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "f499ea0346f340cfb3b175d647bd63c0": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "Alabama",
                    "Arizona",
                    "Arkansas",
                    "California",
                    "Colorado",
                    "Connecticut",
                    "Delaware",
                    "District of Columbia",
                    "Florida",
                    "Georgia",
                    "Hawaii",
                    "Idaho",
                    "Illinois",
                    "Indiana",
                    "Iowa",
                    "Kansas",
                    "Kentucky",
                    "Louisiana",
                    "Maine",
                    "Maryland",
                    "Massachusetts",
                    "Michigan",
                    "Minnesota",
                    "Mississippi",
                    "Missouri",
                    "Montana",
                    "Nebraska",
                    "Nevada",
                    "New Hampshire",
                    "New Jersey",
                    "New Mexico",
                    "New York",
                    "North Carolina",
                    "North Dakota",
                    "Ohio",
                    "Oklahoma",
                    "Oregon",
                    "Pennsylvania",
                    "Puerto Rico",
                    "Rhode Island",
                    "South Carolina",
                    "South Dakota",
                    "Tennessee",
                    "Texas",
                    "Utah",
                    "Vermont",
                    "Virginia",
                    "Washington",
                    "West Virginia",
                    "Wisconsin"
                ],
                "description": "Filing State :",
                "index": 0,
                "layout": "IPY_MODEL_f868b32daf1c4d29918fd5e1d16294ff",
                "style": "IPY_MODEL_95081cb893304eefa1a6907ab5eede12"
            }
        },
        "f4d8a907d00b49499d1ec0f9b09d1f75": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "OCC",
                    "FDIC",
                    "SEC",
                    "FHFA",
                    "CFTC"
                ],
                "description": "Regulator :",
                "index": 0,
                "layout": "IPY_MODEL_adfbd8d1f18f40a9b77e6f7b1c7875cb",
                "style": "IPY_MODEL_0311b4e7262e4332b391555ede1008a8"
            }
        },
        "f4e883db17a847039ac556a28970ba5e": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "f4fb0b80ffa84ddf925b2f3e7c77ce1e": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "f52b17c936a0472b94c7f2a78bcc91c7": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "f55d7cb6eab942cd9bfbc56f54cbc667": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "f55f4c74bfa3461fa464b8bcf451669a": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "f579d2ab060545938bcb69f1896c1a54": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "f5bd69d130874d19a54e4c2bbeba9f9a": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "f5dcc0b6041046c5b77bc7cd131e4a1e": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "f5e33b369a814c8ea8f0cb64ecbf1782": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "f600c4daf81b4576987a11ad96082770": {
            "model_name": "VBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_9a4d9dfc27df41fb80cc94f5bee2a189",
                    "IPY_MODEL_a019e52681c44126b2779df694824942",
                    "IPY_MODEL_5c396b51a18743df8806c160431182b9"
                ],
                "layout": "IPY_MODEL_00b44b962d4e4666ae43a5fd791038b9"
            }
        },
        "f651f59a59754849a6860b9a0c1c2b7e": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "f662763a753a44a88849709613031b7e": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "f6e84cc88dfc4418a0e785e042ecdff9": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "f7005da489e645e0ad47f3aa0c18e0f1": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "Alabama",
                    "Arizona",
                    "Arkansas",
                    "California",
                    "Colorado",
                    "Connecticut",
                    "Delaware",
                    "District of Columbia",
                    "Florida",
                    "Georgia",
                    "Hawaii",
                    "Idaho",
                    "Illinois",
                    "Indiana",
                    "Iowa",
                    "Kansas",
                    "Kentucky",
                    "Louisiana",
                    "Maine",
                    "Maryland",
                    "Massachusetts",
                    "Michigan",
                    "Minnesota",
                    "Mississippi",
                    "Missouri",
                    "Montana",
                    "Nebraska",
                    "Nevada",
                    "New Hampshire",
                    "New Jersey",
                    "New Mexico",
                    "New York",
                    "North Carolina",
                    "North Dakota",
                    "Ohio",
                    "Oklahoma",
                    "Oregon",
                    "Pennsylvania",
                    "Puerto Rico",
                    "Rhode Island",
                    "South Carolina",
                    "South Dakota",
                    "Tennessee",
                    "Texas",
                    "Utah",
                    "Vermont",
                    "Virginia",
                    "Washington",
                    "West Virginia",
                    "Wisconsin"
                ],
                "description": "Filing State :",
                "index": 0,
                "layout": "IPY_MODEL_183d3ef6fc534780b14db5e052b0cf39",
                "style": "IPY_MODEL_2cc8ad71b2b44f0ab9d4a6b4f15d9d32"
            }
        },
        "f7218be0b43447e783988e961c17ee64": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "f7430678863548019d14e75d61145466": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "f765d86bc06b4a04984478730cfaaf3f": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "Alabama",
                    "Arizona",
                    "Arkansas",
                    "California",
                    "Colorado",
                    "Connecticut",
                    "Delaware",
                    "District of Columbia",
                    "Florida",
                    "Georgia",
                    "Hawaii",
                    "Idaho",
                    "Illinois",
                    "Indiana",
                    "Iowa",
                    "Kansas",
                    "Kentucky",
                    "Louisiana",
                    "Maine",
                    "Maryland",
                    "Massachusetts",
                    "Michigan",
                    "Minnesota",
                    "Mississippi",
                    "Missouri",
                    "Montana",
                    "Nebraska",
                    "Nevada",
                    "New Hampshire",
                    "New Jersey",
                    "New Mexico",
                    "New York",
                    "North Carolina",
                    "North Dakota",
                    "Ohio",
                    "Oklahoma",
                    "Oregon",
                    "Pennsylvania",
                    "Puerto Rico",
                    "Rhode Island",
                    "South Carolina",
                    "South Dakota",
                    "Tennessee",
                    "Texas",
                    "Utah",
                    "Vermont",
                    "Virginia",
                    "Washington",
                    "West Virginia",
                    "Wisconsin"
                ],
                "description": "Filing State :",
                "index": 0,
                "layout": "IPY_MODEL_215baec4243b4dbbb3a4c4ba2bc11abd",
                "style": "IPY_MODEL_20222ae82c94433894caf10c800bf6a3"
            }
        },
        "f7b07034dd394a04857e6ef5f9eb971e": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "f7b9db2b98f7454c8c9d0eb6dd9124fc": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "f7c197cd9a8e49eaa293aafc26d9a540": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "f7d2cc10afe34c9897b23f14db8e0419": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "2014",
                    "2019",
                    "2015",
                    "2018",
                    "2017",
                    "2016",
                    "2012",
                    "2013"
                ],
                "description": "Date : ",
                "index": 1,
                "layout": "IPY_MODEL_df0518c255ce4ac891a0c8845dccd3fc",
                "style": "IPY_MODEL_bfcccff3260e4abab90c89b25f3694bf"
            }
        },
        "f811b10e912b4bc28f935ce4595cf622": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "f83c7c5075444caab0c21d859aee6516": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "f857d742aa334822b3a0318cf4de3bea": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "2014",
                    "2019",
                    "2015",
                    "2018",
                    "2017",
                    "2016",
                    "2012",
                    "2013"
                ],
                "description": "Date : ",
                "index": 1,
                "layout": "IPY_MODEL_a3af30c841134eefb2caa73ef02d9b16",
                "style": "IPY_MODEL_33c2db90cafc43c8ba7cf3c740a63874"
            }
        },
        "f868b32daf1c4d29918fd5e1d16294ff": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "f88a6b6c63ae438ea9fb0a9211436a9e": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "f8b8e340a57c41659ae345d0bf11dc07": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "Alabama",
                    "Arizona",
                    "Arkansas",
                    "California",
                    "Colorado",
                    "Connecticut",
                    "Delaware",
                    "District of Columbia",
                    "Florida",
                    "Georgia",
                    "Hawaii",
                    "Idaho",
                    "Illinois",
                    "Indiana",
                    "Iowa",
                    "Kansas",
                    "Kentucky",
                    "Louisiana",
                    "Maine",
                    "Maryland",
                    "Massachusetts",
                    "Michigan",
                    "Minnesota",
                    "Mississippi",
                    "Missouri",
                    "Montana",
                    "Nebraska",
                    "Nevada",
                    "New Hampshire",
                    "New Jersey",
                    "New Mexico",
                    "New York",
                    "North Carolina",
                    "North Dakota",
                    "Ohio",
                    "Oklahoma",
                    "Oregon",
                    "Pennsylvania",
                    "Puerto Rico",
                    "Rhode Island",
                    "South Carolina",
                    "South Dakota",
                    "Tennessee",
                    "Texas",
                    "Utah",
                    "Vermont",
                    "Virginia",
                    "Washington",
                    "West Virginia",
                    "Wisconsin"
                ],
                "description": "Filing State :",
                "index": 0,
                "layout": "IPY_MODEL_66f3148ce1854a9abad8ca1abd976130",
                "style": "IPY_MODEL_8a10ebfb541e4173b44002eeeb3a1e6b"
            }
        },
        "f8e3c4ad09f2462aad166f3cadc97a6b": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "f923f3895c05403894d80347b7dfb99e": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "f9302be0da814fa488a6786df98e9a69": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "OCC",
                    "FDIC",
                    "SEC",
                    "FHFA",
                    "CFTC"
                ],
                "description": "Regulator :",
                "index": 0,
                "layout": "IPY_MODEL_b14ad5306ac94d728db91cbbd9a80a89",
                "style": "IPY_MODEL_8e543b26753a437a9d2ab91b1d8673b4"
            }
        },
        "f930365c5c084daaa47526399074353a": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "OCC",
                    "FDIC",
                    "SEC",
                    "FHFA",
                    "CFTC"
                ],
                "description": "Regulator :",
                "index": 0,
                "layout": "IPY_MODEL_ee0b398463d445d689b43e46b06d07c9",
                "style": "IPY_MODEL_f9fa3b64b34f4b90a800022de58a033a"
            }
        },
        "f93134a8f06f48e68f42be94db95a995": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "f979a5cf4a7d45a98aa2d774d0ce1f0f": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "2014",
                    "2019",
                    "2015",
                    "2018",
                    "2017",
                    "2016",
                    "2012",
                    "2013"
                ],
                "description": "Date : ",
                "index": 1,
                "layout": "IPY_MODEL_c8dfb3779ecb4d3e98dbb417f1c27d3b",
                "style": "IPY_MODEL_3c3e65732aee42a692da7e60570bfce8"
            }
        },
        "f9d073d15ea54a42881600e0e0fd5cd8": {
            "model_name": "FigureModel",
            "model_module": "plotlywidget",
            "model_module_version": "0.9.1",
            "state": {
                "_config": {
                    "plotlyServerURL": "https://plot.ly"
                },
                "_data": [
                    {
                        "orientation": "v",
                        "text": {
                            "dtype": "float64",
                            "shape": [
                                2
                            ]
                        },
                        "textposition": "auto",
                        "type": "bar",
                        "uid": "78c4cda1-1563-4a84-9bea-cee7221ffb24",
                        "x": [
                            "Debit Card",
                            "Deposit Account"
                        ],
                        "y": [
                            223,
                            493
                        ]
                    }
                ],
                "_js2py_restyle": {},
                "_js2py_update": {},
                "_last_layout_edit_id": 1,
                "_layout": {
                    "annotations": [
                        {
                            "font": {
                                "color": "red",
                                "size": 10
                            },
                            "showarrow": false,
                            "text": "Source: FINCEN.gov",
                            "x": 1,
                            "xanchor": "right",
                            "xref": "paper",
                            "xshift": 0,
                            "y": -0.15,
                            "yanchor": "auto",
                            "yref": "paper",
                            "yshift": 0
                        }
                    ],
                    "autosize": true,
                    "barmode": "group",
                    "hovermode": "closest",
                    "template": {},
                    "title": {
                        "text": "SAR Filings by State and Product"
                    }
                },
                "_model_module_version": "0.9.1",
                "_py2js_addTraces": {},
                "_py2js_animate": {},
                "_py2js_deleteTraces": {},
                "_py2js_moveTraces": {},
                "_py2js_removeLayoutProps": {},
                "_py2js_removeTraceProps": {},
                "_py2js_restyle": {},
                "_py2js_update": {},
                "_view_count": 0,
                "_view_module_version": "0.9.1"
            },
            "buffers": [
                {
                    "data": "AAAAAADga0AAAAAAANB+QA==",
                    "path": [
                        "_data",
                        0,
                        "text",
                        "value"
                    ],
                    "encoding": "base64"
                }
            ]
        },
        "f9f79f117b724d3c8179ab0d5dc51321": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "f9fa3b64b34f4b90a800022de58a033a": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "fa73e5b928f14ee2afe597c62e21938e": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "fa8d963946fe40ada4d32710f5467d2f": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_76650e411e544d5995c862d865b727dd"
                ],
                "layout": "IPY_MODEL_6dc0aee9e34c4d41ab23fd4cf5f3a798"
            }
        },
        "fad41783c5514c979d4542433bb21097": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "OCC",
                    "FDIC",
                    "SEC",
                    "FHFA",
                    "CFTC"
                ],
                "description": "Regulator :",
                "index": 0,
                "layout": "IPY_MODEL_543a32044fcf497ebe876f1cc14485dc",
                "style": "IPY_MODEL_0e634793da0a458690e9edce4f4f4418"
            }
        },
        "fb04684418c549ada29ecfe773c13daa": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_f433844b3bd245cf9a38521ec963e0ca",
                    "IPY_MODEL_6dd2aca5cf1a414b800dc1d19eb03e7a"
                ],
                "layout": "IPY_MODEL_474a1d82ab824b1ab57496947f83a48f"
            }
        },
        "fb1d081ff0874208aa475dcf14bf3378": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "OCC",
                    "FDIC",
                    "SEC",
                    "FHFA",
                    "CFTC"
                ],
                "description": "Regulator :",
                "index": 0,
                "layout": "IPY_MODEL_6f6a47b4db504e989a4b4a7c48229b6b",
                "style": "IPY_MODEL_7b2bf586e7b848068e8beb7eb5192900"
            }
        },
        "fb4115655a054371becfec6a82bbf207": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "fb469ce9fad241a585ad9f9c51130bcd": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "fb4ffc46eee345c2b931fd99e62a9d0d": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "fb98974534c34f2d80799a489285c77c": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "2014",
                    "2019",
                    "2015",
                    "2018",
                    "2017",
                    "2016",
                    "2012",
                    "2013"
                ],
                "description": "Date : ",
                "index": 1,
                "layout": "IPY_MODEL_8ae3fc9167134d4baea0b0824c8ab0c7",
                "style": "IPY_MODEL_5451deda00dd43c3b1251347d9e282cc"
            }
        },
        "fbba474f96d241b49477ef4a3154a0a1": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "fbd1d20fd26c4e8dbd806d4133d586c6": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "Alabama",
                    "Arizona",
                    "Arkansas",
                    "California",
                    "Colorado",
                    "Connecticut",
                    "Delaware",
                    "District of Columbia",
                    "Florida",
                    "Georgia",
                    "Hawaii",
                    "Idaho",
                    "Illinois",
                    "Indiana",
                    "Iowa",
                    "Kansas",
                    "Kentucky",
                    "Louisiana",
                    "Maine",
                    "Maryland",
                    "Massachusetts",
                    "Michigan",
                    "Minnesota",
                    "Mississippi",
                    "Missouri",
                    "Montana",
                    "Nebraska",
                    "Nevada",
                    "New Hampshire",
                    "New Jersey",
                    "New Mexico",
                    "New York",
                    "North Carolina",
                    "North Dakota",
                    "Ohio",
                    "Oklahoma",
                    "Oregon",
                    "Pennsylvania",
                    "Puerto Rico",
                    "Rhode Island",
                    "South Carolina",
                    "South Dakota",
                    "Tennessee",
                    "Texas",
                    "Utah",
                    "Vermont",
                    "Virginia",
                    "Washington",
                    "West Virginia",
                    "Wisconsin"
                ],
                "description": "Filing State :",
                "index": 0,
                "layout": "IPY_MODEL_4d96df50977c4b5e9cd31aed99e2c65f",
                "style": "IPY_MODEL_101f2120c5cc44a685ba83cbbbe7b981"
            }
        },
        "fc177883dd514702a1948ccbe50b30f2": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "Alabama",
                    "Arizona",
                    "Arkansas",
                    "California",
                    "Colorado",
                    "Connecticut",
                    "Delaware",
                    "District of Columbia",
                    "Florida",
                    "Georgia",
                    "Hawaii",
                    "Idaho",
                    "Illinois",
                    "Indiana",
                    "Iowa",
                    "Kansas",
                    "Kentucky",
                    "Louisiana",
                    "Maine",
                    "Maryland",
                    "Massachusetts",
                    "Michigan",
                    "Minnesota",
                    "Mississippi",
                    "Missouri",
                    "Montana",
                    "Nebraska",
                    "Nevada",
                    "New Hampshire",
                    "New Jersey",
                    "New Mexico",
                    "New York",
                    "North Carolina",
                    "North Dakota",
                    "Ohio",
                    "Oklahoma",
                    "Oregon",
                    "Pennsylvania",
                    "Puerto Rico",
                    "Rhode Island",
                    "South Carolina",
                    "South Dakota",
                    "Tennessee",
                    "Texas",
                    "Utah",
                    "Vermont",
                    "Virginia",
                    "Washington",
                    "West Virginia",
                    "Wisconsin"
                ],
                "description": "Filing State :",
                "index": 0,
                "layout": "IPY_MODEL_67fbb5690ea84d6b868df2124a3d6007",
                "style": "IPY_MODEL_0ab038dfe46c4f77acffd5fff017922d"
            }
        },
        "fc18a5598118445a8b2f671cc1f9da9b": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "fc2482ab75b944b9a8c43f65daa91e5e": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "2014",
                    "2019",
                    "2015",
                    "2018",
                    "2017",
                    "2016",
                    "2012",
                    "2013"
                ],
                "description": "Date : ",
                "index": 1,
                "layout": "IPY_MODEL_8efef68fdf7e453ab14e0a8e1ff7d146",
                "style": "IPY_MODEL_7e9271c773204535b16137f43f72b507"
            }
        },
        "fcc6da6d479f40e78e3fc03021cd82fe": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "fcd489a197cc4f37bf1d237b19f49c28": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "fcf27945358a43d49433b3dd8d90557e": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "fd35fb1dce334da4807462261ea0513f": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "Alabama",
                    "Arizona",
                    "Arkansas",
                    "California",
                    "Colorado",
                    "Connecticut",
                    "Delaware",
                    "District of Columbia",
                    "Florida",
                    "Georgia",
                    "Hawaii",
                    "Idaho",
                    "Illinois",
                    "Indiana",
                    "Iowa",
                    "Kansas",
                    "Kentucky",
                    "Louisiana",
                    "Maine",
                    "Maryland",
                    "Massachusetts",
                    "Michigan",
                    "Minnesota",
                    "Mississippi",
                    "Missouri",
                    "Montana",
                    "Nebraska",
                    "Nevada",
                    "New Hampshire",
                    "New Jersey",
                    "New Mexico",
                    "New York",
                    "North Carolina",
                    "North Dakota",
                    "Ohio",
                    "Oklahoma",
                    "Oregon",
                    "Pennsylvania",
                    "Puerto Rico",
                    "Rhode Island",
                    "South Carolina",
                    "South Dakota",
                    "Tennessee",
                    "Texas",
                    "Utah",
                    "Vermont",
                    "Virginia",
                    "Washington",
                    "West Virginia",
                    "Wisconsin"
                ],
                "description": "Filing State :",
                "index": 0,
                "layout": "IPY_MODEL_86ab00f63cf541a8bae18e80255ee6b2",
                "style": "IPY_MODEL_27638292e9964acb906ff2c5cae97bd7"
            }
        },
        "fd575400b9a945328719b5309a2d75a7": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "fdccb8d2bd534fc584c0543e63737204": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "fde64528af2242129ad1c4036603aa39": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "2014",
                    "2019",
                    "2015",
                    "2018",
                    "2017",
                    "2016",
                    "2012",
                    "2013"
                ],
                "description": "Date : ",
                "index": 1,
                "layout": "IPY_MODEL_1150476c774e4a0e80bfba722cb7d09b",
                "style": "IPY_MODEL_ba10594bb4d144dab3a4159f6ece265c"
            }
        },
        "fe46e2d4a8544e6a81ca9065f26dad06": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "Alabama",
                    "Arizona",
                    "Arkansas",
                    "California",
                    "Colorado",
                    "Connecticut",
                    "Delaware",
                    "District of Columbia",
                    "Florida",
                    "Georgia",
                    "Hawaii",
                    "Idaho",
                    "Illinois",
                    "Indiana",
                    "Iowa",
                    "Kansas",
                    "Kentucky",
                    "Louisiana",
                    "Maine",
                    "Maryland",
                    "Massachusetts",
                    "Michigan",
                    "Minnesota",
                    "Mississippi",
                    "Missouri",
                    "Montana",
                    "Nebraska",
                    "Nevada",
                    "New Hampshire",
                    "New Jersey",
                    "New Mexico",
                    "New York",
                    "North Carolina",
                    "North Dakota",
                    "Ohio",
                    "Oklahoma",
                    "Oregon",
                    "Pennsylvania",
                    "Puerto Rico",
                    "Rhode Island",
                    "South Carolina",
                    "South Dakota",
                    "Tennessee",
                    "Texas",
                    "Utah",
                    "Vermont",
                    "Virginia",
                    "Washington",
                    "West Virginia",
                    "Wisconsin"
                ],
                "description": "Filing State :",
                "index": 0,
                "layout": "IPY_MODEL_31ae502cec754851891b78c9c04ade71",
                "style": "IPY_MODEL_dc32ebc47a754ed6a9187db60eb2cf96"
            }
        },
        "fe64cbb9e09d498985f08fd40dcc071e": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "2014",
                    "2019",
                    "2015",
                    "2018",
                    "2017",
                    "2016",
                    "2012",
                    "2013"
                ],
                "description": "Date : ",
                "index": 1,
                "layout": "IPY_MODEL_3d74aeaede3d4cd381fb4d1522efa834",
                "style": "IPY_MODEL_95d2ab86984b4872a92d4f49cb98b04d"
            }
        },
        "feb55d41528947fd993e16671bad93c8": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_98ec042639214716afdedaa69dfeb1f0"
                ],
                "layout": "IPY_MODEL_332488ae57004e7a9f2f3cee17b15ae5"
            }
        },
        "feceb0e43b054d01a2bf68e8924bfb74": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "fed9e53e5a7644c9a6598351b971a8c6": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "2014",
                    "2019",
                    "2015",
                    "2018",
                    "2017",
                    "2016",
                    "2012",
                    "2013"
                ],
                "description": "Date : ",
                "index": 1,
                "layout": "IPY_MODEL_f483ff8bda7b43b6a84c5d772c7e16dc",
                "style": "IPY_MODEL_cad7b62ab65b4b41bee4cf3303e77c38"
            }
        },
        "fedd3e0ecc004c30bd704eb225d00107": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "ffcb967e5e064243ad92790e565a6d6b": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "0ac30a669d8e451ba860d75c28fc8f85": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "12ca92d83b54477896f58fb97b6fa052": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "6d9b356ebaf74a8c98165bcf386c0bc2": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "2012",
                    "2013",
                    "2014",
                    "2015",
                    "2016",
                    "2017",
                    "2018",
                    "2019"
                ],
                "description": "Date : ",
                "index": 7,
                "layout": "IPY_MODEL_0ac30a669d8e451ba860d75c28fc8f85",
                "style": "IPY_MODEL_12ca92d83b54477896f58fb97b6fa052"
            }
        },
        "722642b5e455434c9611b81447244587": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "430c80ba17834d8ca4e5ddfe07f216be": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_6d9b356ebaf74a8c98165bcf386c0bc2"
                ],
                "layout": "IPY_MODEL_722642b5e455434c9611b81447244587"
            }
        },
        "f444c18dc74f4f24a6140667701f0a6f": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "970637e3cfb745c79ff08c5d8973cebd": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "7c765d5e99eb4ae8a75a0bc4f9e3ad0e": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "OCC",
                    "FDIC",
                    "SEC",
                    "FHFA",
                    "CFTC"
                ],
                "description": "Regulator :",
                "index": 0,
                "layout": "IPY_MODEL_f444c18dc74f4f24a6140667701f0a6f",
                "style": "IPY_MODEL_970637e3cfb745c79ff08c5d8973cebd"
            }
        },
        "00302d1780c943cf9c97bd9e9a44e029": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "262481145a004ed194ca0257cc262044": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "85b8028396334674a0310ecf37090ad1": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "Alabama",
                    "Arizona",
                    "Arkansas",
                    "California",
                    "Colorado",
                    "Connecticut",
                    "Delaware",
                    "District of Columbia",
                    "Florida",
                    "Georgia",
                    "Hawaii",
                    "Idaho",
                    "Illinois",
                    "Indiana",
                    "Iowa",
                    "Kansas",
                    "Kentucky",
                    "Louisiana",
                    "Maine",
                    "Maryland",
                    "Massachusetts",
                    "Michigan",
                    "Minnesota",
                    "Mississippi",
                    "Missouri",
                    "Montana",
                    "Nebraska",
                    "Nevada",
                    "New Hampshire",
                    "New Jersey",
                    "New Mexico",
                    "New York",
                    "North Carolina",
                    "North Dakota",
                    "Ohio",
                    "Oklahoma",
                    "Oregon",
                    "Pennsylvania",
                    "Puerto Rico",
                    "Rhode Island",
                    "South Carolina",
                    "South Dakota",
                    "Tennessee",
                    "Texas",
                    "Utah",
                    "Vermont",
                    "Virginia",
                    "Washington",
                    "West Virginia",
                    "Wisconsin"
                ],
                "description": "Filing State :",
                "index": 0,
                "layout": "IPY_MODEL_00302d1780c943cf9c97bd9e9a44e029",
                "style": "IPY_MODEL_262481145a004ed194ca0257cc262044"
            }
        },
        "9aeb9c3df92146d190b196ae603c8709": {
            "model_name": "FigureModel",
            "model_module": "plotlywidget",
            "model_module_version": "0.9.1",
            "state": {
                "_config": {
                    "plotlyServerURL": "https://plot.ly"
                },
                "_data": [
                    {
                        "marker": {
                            "color": "rgb(26, 118, 255)",
                            "line": {
                                "color": "rgba(100, 10, 205, 1.0)",
                                "width": 2
                            }
                        },
                        "orientation": "v",
                        "x": [
                            "Debit Card",
                            "Deposit Account"
                        ],
                        "y": [
                            223,
                            493
                        ],
                        "type": "bar",
                        "uid": "f1bcebeb-d078-4a22-84a6-50ad2d77c75c"
                    }
                ],
                "_js2py_pointsCallback": {},
                "_js2py_restyle": {},
                "_js2py_update": {},
                "_last_layout_edit_id": 1,
                "_layout": {
                    "annotations": [
                        {
                            "font": {
                                "color": "red",
                                "size": 10
                            },
                            "showarrow": false,
                            "text": "Source: FINCEN.gov",
                            "x": 1,
                            "xanchor": "right",
                            "xref": "paper",
                            "xshift": 0,
                            "y": -0.15,
                            "yanchor": "auto",
                            "yref": "paper",
                            "yshift": 0
                        }
                    ],
                    "barmode": "group",
                    "hovermode": "closest",
                    "paper_bgcolor": "whitesmoke",
                    "plot_bgcolor": "whitesmoke",
                    "shapes": [
                        {
                            "line": {
                                "color": "RoyalBlue"
                            },
                            "type": "rect",
                            "x0": 0,
                            "x1": 0,
                            "y0": 0,
                            "y1": 0
                        }
                    ],
                    "title": {
                        "text": "Number SAR Filings by State and Product"
                    },
                    "template": {},
                    "autosize": true
                },
                "_model_module_version": "0.9.1",
                "_py2js_addTraces": {},
                "_py2js_animate": {},
                "_py2js_deleteTraces": {},
                "_py2js_moveTraces": {},
                "_py2js_removeLayoutProps": {},
                "_py2js_removeTraceProps": {},
                "_py2js_restyle": {},
                "_py2js_update": {},
                "_view_count": 0,
                "_view_module_version": "0.9.1"
            }
        },
        "5874cf32c55d4956920fb8c646ccba3a": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "ee05ac486ca149c3961f028e0b52f464": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_85b8028396334674a0310ecf37090ad1",
                    "IPY_MODEL_7c765d5e99eb4ae8a75a0bc4f9e3ad0e"
                ],
                "layout": "IPY_MODEL_5874cf32c55d4956920fb8c646ccba3a"
            }
        },
        "d91bf9c06657416cb783a03d87f10ce0": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "6f73979788a24132bda38186340018cf": {
            "model_name": "VBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_430c80ba17834d8ca4e5ddfe07f216be",
                    "IPY_MODEL_ee05ac486ca149c3961f028e0b52f464",
                    "IPY_MODEL_9aeb9c3df92146d190b196ae603c8709"
                ],
                "layout": "IPY_MODEL_d91bf9c06657416cb783a03d87f10ce0"
            }
        },
        "8ebb50d0082e444fac5b19a44169c50f": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "3e10b39dc0a34e0d932bad2985df7350": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "97d13cd2025f458ca4c616f380b4dfa0": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "2012",
                    "2013",
                    "2014",
                    "2015",
                    "2016",
                    "2017",
                    "2018",
                    "2019"
                ],
                "description": "Date : ",
                "index": 7,
                "layout": "IPY_MODEL_8ebb50d0082e444fac5b19a44169c50f",
                "style": "IPY_MODEL_3e10b39dc0a34e0d932bad2985df7350"
            }
        },
        "95696be9b3e048c48d533a3d97a2fa5c": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "67a20525fac14fcca7c0068cd3e90f46": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_97d13cd2025f458ca4c616f380b4dfa0"
                ],
                "layout": "IPY_MODEL_95696be9b3e048c48d533a3d97a2fa5c"
            }
        },
        "36594adf150146da873ba3f747d95533": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "6fe0195fc4424a659890c2e41bdfa4cc": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "f15bbe743b584a4e999c9d9ff3662a21": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "OCC",
                    "FDIC",
                    "SEC",
                    "FHFA",
                    "CFTC"
                ],
                "description": "Regulator :",
                "index": 0,
                "layout": "IPY_MODEL_36594adf150146da873ba3f747d95533",
                "style": "IPY_MODEL_6fe0195fc4424a659890c2e41bdfa4cc"
            }
        },
        "d96e6bfa4f6c4841a551a35ae578a657": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "bc27a2ba2df84816b41ce281d32fc7de": {
            "model_name": "DescriptionStyleModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "description_width": ""
            }
        },
        "dd31e7d891f8464885e990200fde73d1": {
            "model_name": "DropdownModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "_options_labels": [
                    "Alabama",
                    "Arizona",
                    "Arkansas",
                    "California",
                    "Colorado",
                    "Connecticut",
                    "Delaware",
                    "District of Columbia",
                    "Florida",
                    "Georgia",
                    "Hawaii",
                    "Idaho",
                    "Illinois",
                    "Indiana",
                    "Iowa",
                    "Kansas",
                    "Kentucky",
                    "Louisiana",
                    "Maine",
                    "Maryland",
                    "Massachusetts",
                    "Michigan",
                    "Minnesota",
                    "Mississippi",
                    "Missouri",
                    "Montana",
                    "Nebraska",
                    "Nevada",
                    "New Hampshire",
                    "New Jersey",
                    "New Mexico",
                    "New York",
                    "North Carolina",
                    "North Dakota",
                    "Ohio",
                    "Oklahoma",
                    "Oregon",
                    "Pennsylvania",
                    "Puerto Rico",
                    "Rhode Island",
                    "South Carolina",
                    "South Dakota",
                    "Tennessee",
                    "Texas",
                    "Utah",
                    "Vermont",
                    "Virginia",
                    "Washington",
                    "West Virginia",
                    "Wisconsin"
                ],
                "description": "Filing State :",
                "index": 31,
                "layout": "IPY_MODEL_d96e6bfa4f6c4841a551a35ae578a657",
                "style": "IPY_MODEL_bc27a2ba2df84816b41ce281d32fc7de"
            }
        },
        "d0b0e547a23a42ad9905a5a7146649d1": {
            "model_name": "FigureModel",
            "model_module": "plotlywidget",
            "model_module_version": "0.9.1",
            "state": {
                "_config": {
                    "plotlyServerURL": "https://plot.ly"
                },
                "_data": [
                    {
                        "marker": {
                            "color": "rgb(26, 118, 255)",
                            "line": {
                                "color": "rgba(100, 10, 205, 1.0)",
                                "width": 2
                            }
                        },
                        "orientation": "v",
                        "x": [
                            "Credit Card",
                            "Debit Card",
                            "Deposit Account"
                        ],
                        "y": [
                            1045,
                            13804,
                            24168
                        ],
                        "type": "bar",
                        "uid": "60e331e9-f82f-417e-befb-6b773fa32208"
                    }
                ],
                "_js2py_restyle": {},
                "_js2py_update": {},
                "_last_layout_edit_id": 7,
                "_last_trace_edit_id": 5,
                "_layout": {
                    "annotations": [
                        {
                            "font": {
                                "color": "red",
                                "size": 10
                            },
                            "showarrow": false,
                            "text": "Source: FINCEN.gov",
                            "x": 1,
                            "xanchor": "right",
                            "xref": "paper",
                            "xshift": 0,
                            "y": -0.15,
                            "yanchor": "auto",
                            "yref": "paper",
                            "yshift": 0
                        }
                    ],
                    "barmode": "group",
                    "hovermode": "closest",
                    "paper_bgcolor": "whitesmoke",
                    "plot_bgcolor": "whitesmoke",
                    "shapes": [
                        {
                            "line": {
                                "color": "RoyalBlue"
                            },
                            "type": "rect",
                            "x0": 0,
                            "x1": 0,
                            "y0": 0,
                            "y1": 0
                        }
                    ],
                    "title": {
                        "text": "Number SAR Filings by State and Product"
                    },
                    "template": {},
                    "autosize": true,
                    "xaxis": {
                        "title": {
                            "text": "SARs Filing Type"
                        },
                        "showspikes": true
                    },
                    "yaxis": {
                        "title": {
                            "text": "Number of Filings"
                        },
                        "showspikes": true
                    }
                },
                "_model_module_version": "0.9.1",
                "_py2js_addTraces": {},
                "_py2js_animate": {},
                "_py2js_deleteTraces": {},
                "_py2js_moveTraces": {},
                "_py2js_removeLayoutProps": {},
                "_py2js_removeTraceProps": {},
                "_py2js_restyle": {},
                "_view_count": 1,
                "_view_module_version": "0.9.1"
            }
        },
        "2991c53789e6483492bbd559ea795928": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "01766626b5db4f97baa9ab1019ccade9": {
            "model_name": "HBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_dd31e7d891f8464885e990200fde73d1",
                    "IPY_MODEL_f15bbe743b584a4e999c9d9ff3662a21"
                ],
                "layout": "IPY_MODEL_2991c53789e6483492bbd559ea795928"
            }
        },
        "c49cda5210924b439cdc4d54ac0a228c": {
            "model_name": "LayoutModel",
            "model_module": "@jupyter-widgets/base",
            "model_module_version": "1.2.0",
            "state": {}
        },
        "2692b19b44964588abd1a0b843f91abd": {
            "model_name": "VBoxModel",
            "model_module": "@jupyter-widgets/controls",
            "model_module_version": "1.5.0",
            "state": {
                "children": [
                    "IPY_MODEL_67a20525fac14fcca7c0068cd3e90f46",
                    "IPY_MODEL_01766626b5db4f97baa9ab1019ccade9",
                    "IPY_MODEL_d0b0e547a23a42ad9905a5a7146649d1"
                ],
                "layout": "IPY_MODEL_c49cda5210924b439cdc4d54ac0a228c"
            }
        }
    }
}
</script>
</head>
<body>

<script type="application/vnd.jupyter.widget-view+json">
{
    "version_major": 2,
    "version_minor": 0,
    "model_id": "2692b19b44964588abd1a0b843f91abd"
}
</script>

</body>
</html>

<hr>
<br />

<div class="poweredBy" style="font-family: Arial, Helvetica, sans-serif;"><span style="font-size: 15px;color: #333333;text-decoration: none;">Data provided by <a rel="nofollow" target="_blank" style="font-size: 15px;color: #06529D; font-weight: bold;" class="underline_link" align="right">World Bank Open Data</a></span>
  <br />
  <form action="https://databank.worldbank.org/data/databases/page/1/orderby/popularity/direction/desc?qterm=&404-search-button=Search" method="GET">
    <input type="text" id="search" name="qterm" placeholder="Explore, gdp, inflation, unemployment">
    <button type="submit" id="submit" style="background-color:#687f9f;color:white"> Search </button>
  </form>
  <h5 data-reactid=""><span data-reactid="">Browse by</span><a href="https://data.worldbank.org/country" data-reactid=""><span data-reactid=""> Country </span></a><span data-reactid="">or</span><a href="https://data.worldbank.org/indicator" data-reactid=""><span data-reactid=""> Indicator </span></a></h5>
</div>

<iframe src="https://data.worldbank.org/share/widget?end=2013&indicators=EN.ATM.CO2E.KT&locations=1W&start=1960&view=chart" width='100%' height='450' frameBorder='0' ></iframe>

<hr>
<br/>
<div class="poweredBy" style="font-family: Arial, Helvetica, sans-serif;"><span style="font-size: 15px;color: #333333;text-decoration: none;">Data provided by <a href="https://data.nber.org/data/" rel="nofollow" target="_blank" style="font-size: 15px;color: #06529D; font-weight: bold;" class="underline_link" align="right">National Bureau of Economic Research - NBER</a></span>
<br />
  <form action="https://admin.nber.org/xsearch?q=&whichsearch=ftpub-search-button=Search" method="GET">
    <input type="text" id="search" name="q" placeholder="Search the NBER site">
    <button type="submit" id="submit" style="background-color:#687f9f;color:white">Search</button>
  </form>
</div>

<br /><br />
<h1 class="section-front-header-module__title">Supply Chain</h1>

    Under Construction, though the link below provides some examples.

<div class="poweredBy" style="font-family: Arial, Helvetica, sans-serif;"><span style="font-size: 18px;color: #333333;text-decoration: none;">Data provided by <a href="https://catalog.data.gov/dataset?tags=supply-chain" rel="nofollow" target="_blank" style="font-size: 15px;color: #06529D; font-weight: bold;" class="underline_link" align="right">The home of the U.S. Government’s open data</a></span>

<div class="poweredBy" style="font-family: Arial, Helvetica, sans-serif;"><span style="font-size: 18px;color: #333333;text-decoration: none;">Data provided by <a href="https://coral.ise.lehigh.edu/sctheory/data-sets/" rel="nofollow" target="_blank" style="font-size: 15px;color: #06529D; font-weight: bold;" class="underline_link" align="right">Fundamentals of Supply Chain Theory - Lehigh CORAL</a></span>

<div class="poweredBy" style="font-family: Arial, Helvetica, sans-serif;"><span style="font-size: 18px;color: #333333;text-decoration: none;">Data provided by <a href="https://brunel.figshare.com/browse" rel="nofollow" target="_blank" style="font-size: 15px;color: #06529D; font-weight: bold;" class="underline_link" align="right">Brunel University London</a></span>

<hr>
<br />
<h1 class="section-front-header-module__title">Other Tools & DataSets</h1>

    Under Construction, though the link below provides some examples.

<div class="poweredBy" style="font-family: Arial, Helvetica, sans-serif;"><span style="font-size: 15px;color: #333333;text-decoration: none;"><a href="https://github.com/LuisFRoch/Excel-Tools" rel="nofollow" target="_blank" style="font-size: 14px;color: #06529D; font-weight: bold;" class="underline_link" align="right">Excel Macros to help with daily workload...More...</a></span></div>
<hr>

<br />
