{
	"boxes" : [ 		{
			"box" : 			{
				"maxclass" : "bpatcher",
				"annotation" : "## Create video \"meta images\"## ",
				"varname" : "fractalizr",
				"prototypename" : "pixl",
				"viewvisibility" : 1,
				"offset" : [ 0.0, 0.0 ],
				"lockeddragscroll" : 0,
				"clickthrough" : 0,
				"enablehscroll" : 0,
				"enablevscroll" : 0,
				"bgmode" : 1,
				"border" : 0,
				"id" : "obj-2",
				"name" : "vz.fractalizr.maxpat",
				"outlettype" : [ "jit_matrix" ],
				"numinlets" : 5,
				"patching_rect" : [ 326.333344, 743.333313, 258.0, 130.0 ],
				"numoutlets" : 1
			}

		}
, 		{
			"box" : 			{
				"maxclass" : "newobj",
				"text" : "/ 30.",
				"id" : "obj-39",
				"style" : "",
				"outlettype" : [ "float" ],
				"numinlets" : 2,
				"patching_rect" : [ 682.0, 161.0, 34.0, 22.0 ],
				"numoutlets" : 1
			}

		}
, 		{
			"box" : 			{
				"maxclass" : "newobj",
				"text" : "counter 10",
				"id" : "obj-71",
				"style" : "",
				"outlettype" : [ "int", "", "", "int" ],
				"numinlets" : 5,
				"patching_rect" : [ 682.0, 122.0, 67.0, 22.0 ],
				"numoutlets" : 4
			}

		}
, 		{
			"box" : 			{
				"maxclass" : "button",
				"id" : "obj-70",
				"style" : "",
				"outlettype" : [ "bang" ],
				"numinlets" : 1,
				"patching_rect" : [ 23.0, 46.0, 24.0, 24.0 ],
				"numoutlets" : 1
			}

		}
, 		{
			"box" : 			{
				"maxclass" : "flonum",
				"id" : "obj-67",
				"parameter_enable" : 0,
				"style" : "",
				"outlettype" : [ "", "bang" ],
				"numinlets" : 1,
				"format" : 6,
				"patching_rect" : [ 670.0, 218.0, 50.0, 22.0 ],
				"numoutlets" : 2
			}

		}
, 		{
			"box" : 			{
				"maxclass" : "button",
				"id" : "obj-63",
				"style" : "",
				"outlettype" : [ "bang" ],
				"numinlets" : 1,
				"patching_rect" : [ 670.0, 67.0, 24.0, 24.0 ],
				"numoutlets" : 1
			}

		}
, 		{
			"box" : 			{
				"maxclass" : "slider",
				"id" : "obj-52",
				"parameter_enable" : 0,
				"style" : "",
				"size" : 1.0,
				"outlettype" : [ "" ],
				"floatoutput" : 1,
				"mult" : 0.99,
				"numinlets" : 1,
				"patching_rect" : [ 773.333252, 212.0, 20.0, 140.0 ],
				"numoutlets" : 1
			}

		}
, 		{
			"box" : 			{
				"maxclass" : "button",
				"id" : "obj-43",
				"style" : "",
				"outlettype" : [ "bang" ],
				"numinlets" : 1,
				"patching_rect" : [ 944.500061, 622.333313, 24.0, 24.0 ],
				"numoutlets" : 1
			}

		}
, 		{
			"box" : 			{
				"maxclass" : "newobj",
				"text" : "-",
				"id" : "obj-32",
				"style" : "",
				"outlettype" : [ "int" ],
				"numinlets" : 2,
				"patching_rect" : [ 941.750061, 666.333313, 29.5, 22.0 ],
				"numoutlets" : 1
			}

		}
, 		{
			"box" : 			{
				"maxclass" : "message",
				"text" : "0.25",
				"id" : "obj-33",
				"style" : "",
				"outlettype" : [ "" ],
				"numinlets" : 2,
				"patching_rect" : [ 893.666687, 666.333313, 34.0, 22.0 ],
				"numoutlets" : 1
			}

		}
, 		{
			"box" : 			{
				"maxclass" : "button",
				"id" : "obj-30",
				"style" : "",
				"outlettype" : [ "bang" ],
				"numinlets" : 1,
				"patching_rect" : [ 825.666687, 710.333313, 24.0, 24.0 ],
				"numoutlets" : 1
			}

		}
, 		{
			"box" : 			{
				"maxclass" : "newobj",
				"text" : "+",
				"id" : "obj-28",
				"style" : "",
				"outlettype" : [ "int" ],
				"numinlets" : 2,
				"patching_rect" : [ 831.000061, 666.333313, 29.5, 22.0 ],
				"numoutlets" : 1
			}

		}
, 		{
			"box" : 			{
				"maxclass" : "message",
				"text" : "0.25",
				"id" : "obj-27",
				"style" : "",
				"outlettype" : [ "" ],
				"numinlets" : 2,
				"patching_rect" : [ 785.666687, 666.333313, 34.0, 22.0 ],
				"numoutlets" : 1
			}

		}
, 		{
			"box" : 			{
				"maxclass" : "slider",
				"id" : "obj-25",
				"parameter_enable" : 0,
				"style" : "",
				"size" : 4.0,
				"outlettype" : [ "" ],
				"floatoutput" : 1,
				"numinlets" : 1,
				"patching_rect" : [ 1054.333252, 648.0, 20.0, 140.0 ],
				"numoutlets" : 1
			}

		}
, 		{
			"box" : 			{
				"maxclass" : "slider",
				"id" : "obj-22",
				"parameter_enable" : 0,
				"style" : "",
				"size" : 99.0,
				"outlettype" : [ "" ],
				"floatoutput" : 1,
				"mult" : 0.99,
				"numinlets" : 1,
				"patching_rect" : [ 445.333344, 428.0, 20.0, 140.0 ],
				"numoutlets" : 1
			}

		}
, 		{
			"box" : 			{
				"maxclass" : "slider",
				"id" : "obj-10",
				"parameter_enable" : 0,
				"style" : "",
				"size" : 99.0,
				"outlettype" : [ "" ],
				"floatoutput" : 1,
				"mult" : 0.99,
				"numinlets" : 1,
				"patching_rect" : [ 409.333344, 428.0, 20.0, 140.0 ],
				"numoutlets" : 1
			}

		}
, 		{
			"box" : 			{
				"maxclass" : "bpatcher",
				"annotation" : "## A dial/display for VIZZIE data ##",
				"varname" : "twistr",
				"viewvisibility" : 1,
				"offset" : [ 0.0, 0.0 ],
				"lockeddragscroll" : 0,
				"clickthrough" : 0,
				"enablehscroll" : 0,
				"enablevscroll" : 0,
				"bgmode" : 1,
				"border" : 0,
				"id" : "obj-1",
				"name" : "vz.twistr.maxpat",
				"outlettype" : [ "" ],
				"numinlets" : 1,
				"patching_rect" : [ 860.666626, 137.333313, 88.0, 108.0 ],
				"numoutlets" : 1
			}

		}
, 		{
			"box" : 			{
				"maxclass" : "bpatcher",
				"annotation" : "## The VIZZIE video player/looper ##",
				"varname" : "playr",
				"prototypename" : "pixl",
				"viewvisibility" : 1,
				"offset" : [ 0.0, 0.0 ],
				"lockeddragscroll" : 0,
				"clickthrough" : 0,
				"enablehscroll" : 0,
				"enablevscroll" : 0,
				"bgmode" : 1,
				"border" : 0,
				"id" : "obj-6",
				"name" : "vz.playr.maxpat",
				"outlettype" : [ "jit_matrix", "" ],
				"numinlets" : 5,
				"patching_rect" : [ 620.500061, 419.0, 348.0, 158.0 ],
				"numoutlets" : 2
			}

		}
, 		{
			"box" : 			{
				"maxclass" : "bpatcher",
				"annotation" : "## Load a folder with videos for VIZZIE ##",
				"varname" : "moviefoldr",
				"prototypename" : "pixl",
				"viewvisibility" : 1,
				"offset" : [ 0.0, 0.0 ],
				"lockeddragscroll" : 0,
				"clickthrough" : 0,
				"enablehscroll" : 0,
				"enablevscroll" : 0,
				"bgmode" : 1,
				"border" : 0,
				"id" : "obj-3",
				"name" : "vz.moviefoldr.maxpat",
				"outlettype" : [ "" ],
				"numinlets" : 1,
				"patching_rect" : [ 860.666626, 272.0, 241.0, 98.0 ],
				"numoutlets" : 1
			}

		}
, 		{
			"box" : 			{
				"maxclass" : "bpatcher",
				"annotation" : "## 4-input video mixer ##",
				"varname" : "4mixr",
				"prototypename" : "pixl",
				"viewvisibility" : 1,
				"offset" : [ 0.0, 0.0 ],
				"lockeddragscroll" : 0,
				"clickthrough" : 0,
				"enablehscroll" : 0,
				"enablevscroll" : 0,
				"bgmode" : 1,
				"border" : 0,
				"id" : "obj-21",
				"name" : "vz.4mixr.maxpat",
				"outlettype" : [ "jit_matrix" ],
				"numinlets" : 9,
				"patching_rect" : [ 258.458344, 599.333374, 318.0, 130.0 ],
				"numoutlets" : 1
			}

		}
, 		{
			"box" : 			{
				"maxclass" : "flonum",
				"id" : "obj-42",
				"parameter_enable" : 0,
				"style" : "",
				"outlettype" : [ "", "bang" ],
				"numinlets" : 1,
				"format" : 6,
				"patching_rect" : [ 169.0, 288.0, 50.0, 22.0 ],
				"numoutlets" : 2
			}

		}
, 		{
			"box" : 			{
				"maxclass" : "flonum",
				"id" : "obj-40",
				"parameter_enable" : 0,
				"style" : "",
				"outlettype" : [ "", "bang" ],
				"numinlets" : 1,
				"format" : 6,
				"patching_rect" : [ 83.0, 288.0, 50.0, 22.0 ],
				"numoutlets" : 2
			}

		}
, 		{
			"box" : 			{
				"maxclass" : "flonum",
				"id" : "obj-38",
				"parameter_enable" : 0,
				"style" : "",
				"outlettype" : [ "", "bang" ],
				"numinlets" : 1,
				"format" : 6,
				"patching_rect" : [ 16.0, 288.0, 50.0, 22.0 ],
				"numoutlets" : 2
			}

		}
, 		{
			"box" : 			{
				"maxclass" : "newobj",
				"text" : "random 99",
				"id" : "obj-36",
				"style" : "",
				"outlettype" : [ "int" ],
				"numinlets" : 2,
				"patching_rect" : [ 186.5, 246.0, 68.0, 22.0 ],
				"numoutlets" : 1
			}

		}
, 		{
			"box" : 			{
				"maxclass" : "newobj",
				"text" : "random 99",
				"id" : "obj-35",
				"style" : "",
				"outlettype" : [ "int" ],
				"numinlets" : 2,
				"patching_rect" : [ 96.5, 246.0, 68.0, 22.0 ],
				"numoutlets" : 1
			}

		}
, 		{
			"box" : 			{
				"maxclass" : "newobj",
				"text" : "random 99",
				"id" : "obj-23",
				"style" : "",
				"outlettype" : [ "int" ],
				"numinlets" : 2,
				"patching_rect" : [ 16.0, 246.0, 68.0, 22.0 ],
				"numoutlets" : 1
			}

		}
, 		{
			"box" : 			{
				"maxclass" : "button",
				"id" : "obj-20",
				"style" : "",
				"outlettype" : [ "bang" ],
				"numinlets" : 1,
				"patching_rect" : [ 23.0, 203.0, 24.0, 24.0 ],
				"numoutlets" : 1
			}

		}
, 		{
			"box" : 			{
				"maxclass" : "slider",
				"id" : "obj-16",
				"parameter_enable" : 0,
				"style" : "",
				"size" : 99.0,
				"outlettype" : [ "" ],
				"floatoutput" : 1,
				"mult" : 0.99,
				"numinlets" : 1,
				"patching_rect" : [ 132.0, 327.333313, 20.0, 140.0 ],
				"numoutlets" : 1
			}

		}
, 		{
			"box" : 			{
				"maxclass" : "slider",
				"id" : "obj-14",
				"parameter_enable" : 0,
				"style" : "",
				"size" : 99.0,
				"outlettype" : [ "" ],
				"floatoutput" : 1,
				"mult" : 0.99,
				"numinlets" : 1,
				"patching_rect" : [ 51.0, 341.0, 20.0, 140.0 ],
				"numoutlets" : 1
			}

		}
, 		{
			"box" : 			{
				"maxclass" : "slider",
				"id" : "obj-12",
				"parameter_enable" : 0,
				"style" : "",
				"size" : 99.0,
				"outlettype" : [ "" ],
				"floatoutput" : 1,
				"mult" : 0.99,
				"numinlets" : 1,
				"patching_rect" : [ 90.0, 341.0, 20.0, 140.0 ],
				"numoutlets" : 1
			}

		}
, 		{
			"box" : 			{
				"maxclass" : "bpatcher",
				"annotation" : "## Turn a video into dust ##",
				"varname" : "foggr",
				"prototypename" : "pixl",
				"viewvisibility" : 1,
				"offset" : [ 0.0, 0.0 ],
				"lockeddragscroll" : 0,
				"clickthrough" : 0,
				"enablehscroll" : 0,
				"enablevscroll" : 0,
				"bgmode" : 1,
				"border" : 0,
				"id" : "obj-9",
				"name" : "vz.foggr.maxpat",
				"outlettype" : [ "jit_matrix" ],
				"embed" : 1,
				"numinlets" : 4,
				"patching_rect" : [ 41.0, 743.333313, 188.0, 130.0 ],
				"numoutlets" : 1,
				"patcher" : 				{
					"fileversion" : 1,
					"appversion" : 					{
						"major" : 7,
						"minor" : 3,
						"revision" : 1,
						"architecture" : "x86",
						"modernui" : 1
					}
,
					"rect" : [ 69.0, 665.0, 141.0, 98.0 ],
					"bgcolor" : [ 0.5, 0.8, 0.5, 1.0 ],
					"bglocked" : 0,
					"openinpresentation" : 1,
					"default_fontsize" : 12.0,
					"default_fontface" : 0,
					"default_fontname" : "Arial",
					"gridonopen" : 1,
					"gridsize" : [ 8.0, 8.0 ],
					"gridsnaponopen" : 1,
					"objectsnaponopen" : 1,
					"statusbarvisible" : 2,
					"toolbarvisible" : 1,
					"lefttoolbarpinned" : 0,
					"toptoolbarpinned" : 0,
					"righttoolbarpinned" : 0,
					"bottomtoolbarpinned" : 0,
					"toolbars_unpinned_last_save" : 0,
					"tallnewobj" : 0,
					"boxanimatetime" : 200,
					"enablehscroll" : 0,
					"enablevscroll" : 0,
					"devicewidth" : 0.0,
					"description" : "Create fogging or spattering effects",
					"digest" : "",
					"tags" : "Vizzie Effect",
					"style" : "",
					"subpatcher_template" : "",
					"boxes" : [ 						{
							"box" : 							{
								"maxclass" : "comment",
								"hint" : "The FOGGR module (based on the jit.sprinkle object) is specially calibrated to blow your images to smithereens and spread the cloud of pixel dust horizontally and/or vertically to suit your needs. You can even decide how much of this dusty mayhem to add to your image by setting the module's probability.",
								"text" : "FOGGR",
								"id" : "obj-83",
								"style" : "",
								"fontsize" : 9.0,
								"presentation_rect" : [ 3.474808, 17.0, 43.0, 17.0 ],
								"fontname" : "Arial Bold",
								"numinlets" : 1,
								"patching_rect" : [ 29.609558, 355.771027, 50.0, 17.0 ],
								"textcolor" : [ 1.0, 1.0, 1.0, 1.0 ],
								"presentation" : 1,
								"numoutlets" : 0
							}

						}
, 						{
							"box" : 							{
								"maxclass" : "newobj",
								"text" : "unpack i i",
								"id" : "obj-12",
								"style" : "",
								"fontsize" : 12.0,
								"outlettype" : [ "int", "int" ],
								"fontname" : "Arial",
								"numinlets" : 1,
								"patching_rect" : [ 1001.0, 179.498413, 61.0, 20.0 ],
								"numoutlets" : 2
							}

						}
, 						{
							"box" : 							{
								"maxclass" : "newobj",
								"text" : "s askme",
								"id" : "obj-10",
								"style" : "",
								"fontsize" : 12.0,
								"fontname" : "Arial",
								"numinlets" : 1,
								"patching_rect" : [ 949.0, 109.73999, 55.0, 20.0 ],
								"numoutlets" : 0
							}

						}
, 						{
							"box" : 							{
								"maxclass" : "newobj",
								"text" : "loadbang",
								"id" : "obj-9",
								"style" : "",
								"fontsize" : 12.0,
								"outlettype" : [ "bang" ],
								"fontname" : "Arial",
								"numinlets" : 1,
								"patching_rect" : [ 949.0, 72.73999, 60.0, 20.0 ],
								"numoutlets" : 1
							}

						}
, 						{
							"box" : 							{
								"maxclass" : "newobj",
								"text" : "r output_dim",
								"id" : "obj-8",
								"style" : "",
								"fontsize" : 12.0,
								"outlettype" : [ "" ],
								"fontname" : "Arial",
								"numinlets" : 0,
								"patching_rect" : [ 1001.0, 153.73999, 77.0, 20.0 ],
								"numoutlets" : 1
							}

						}
, 						{
							"box" : 							{
								"maxclass" : "textbutton",
								"hint" : "Click on the bar to turn the effect on or off. The image is passed through without any processing when the effect is off.",
								"varname" : "FreqMode[3]",
								"id" : "obj-3",
								"usebgoncolor" : 1,
								"parameter_enable" : 1,
								"style" : "",
								"fontsize" : 9.0,
								"outlettype" : [ "", "", "int" ],
								"bgoncolor" : [ 0.184314, 0.443137, 0.258824, 1.0 ],
								"align" : 2,
								"textjustification" : 2,
								"presentation_rect" : [ 0.474808, 16.0, 188.0, 19.0 ],
								"mode" : 1,
								"texton" : "ON  ",
								"fontname" : "Arial Bold",
								"numinlets" : 1,
								"legacytextcolor" : 1,
								"text" : "OFF  ",
								"textoncolor" : [ 0.905882, 0.909804, 0.917647, 1.0 ],
								"bgcolor" : [ 0.3, 0.3, 0.3, 1.0 ],
								"patching_rect" : [ 277.0, 224.0, 40.0, 20.0 ],
								"textcolor" : [ 1.0, 1.0, 1.0, 1.0 ],
								"presentation" : 1,
								"numoutlets" : 3,
								"saved_attribute_attributes" : 								{
									"valueof" : 									{
										"parameter_longname" : "range[7]",
										"parameter_shortname" : "range",
										"parameter_type" : 3,
										"parameter_initial_enable" : 1,
										"parameter_initial" : [ 1 ],
										"parameter_invisible" : 1
									}

								}

							}

						}
, 						{
							"box" : 							{
								"maxclass" : "newobj",
								"text" : "scale 0. 1. 0. 100.",
								"id" : "obj-54",
								"style" : "",
								"fontsize" : 12.0,
								"outlettype" : [ "" ],
								"fontname" : "Arial",
								"numinlets" : 6,
								"patching_rect" : [ 751.0, 224.0, 105.0, 20.0 ],
								"numoutlets" : 1
							}

						}
, 						{
							"box" : 							{
								"maxclass" : "newobj",
								"text" : "scale 0. 1. 0. 100.",
								"id" : "obj-53",
								"style" : "",
								"fontsize" : 12.0,
								"outlettype" : [ "" ],
								"fontname" : "Arial",
								"numinlets" : 6,
								"patching_rect" : [ 600.0, 224.0, 105.0, 20.0 ],
								"numoutlets" : 1
							}

						}
, 						{
							"box" : 							{
								"maxclass" : "newobj",
								"text" : "scale 0. 1. 0. 100.",
								"id" : "obj-52",
								"style" : "",
								"fontsize" : 12.0,
								"outlettype" : [ "" ],
								"fontname" : "Arial",
								"numinlets" : 6,
								"patching_rect" : [ 440.0, 224.0, 105.0, 20.0 ],
								"numoutlets" : 1
							}

						}
, 						{
							"box" : 							{
								"maxclass" : "newobj",
								"text" : "scale 0. 100. 0. 1.",
								"id" : "obj-51",
								"style" : "",
								"fontsize" : 12.0,
								"outlettype" : [ "" ],
								"fontname" : "Arial",
								"numinlets" : 6,
								"patching_rect" : [ 440.0, 369.0, 105.0, 20.0 ],
								"numoutlets" : 1
							}

						}
, 						{
							"box" : 							{
								"maxclass" : "newobj",
								"varname" : "y_range",
								"text" : "pattr y_range",
								"id" : "obj-11",
								"style" : "",
								"fontsize" : 12.0,
								"outlettype" : [ "", "", "" ],
								"fontname" : "Arial",
								"numinlets" : 1,
								"patching_rect" : [ 775.0, 196.0, 81.0, 20.0 ],
								"numoutlets" : 3,
								"restore" : [ 25.0 ],
								"saved_object_attributes" : 								{
									"parameter_enable" : 0
								}

							}

						}
, 						{
							"box" : 							{
								"maxclass" : "newobj",
								"varname" : "x_range",
								"text" : "pattr x_range",
								"id" : "obj-7",
								"style" : "",
								"fontsize" : 12.0,
								"outlettype" : [ "", "", "" ],
								"fontname" : "Arial",
								"numinlets" : 1,
								"patching_rect" : [ 619.0, 196.0, 81.0, 20.0 ],
								"numoutlets" : 3,
								"restore" : [ 75.0 ],
								"saved_object_attributes" : 								{
									"parameter_enable" : 0
								}

							}

						}
, 						{
							"box" : 							{
								"maxclass" : "newobj",
								"varname" : "prob",
								"text" : "pattr prob",
								"id" : "obj-6",
								"style" : "",
								"fontsize" : 12.0,
								"outlettype" : [ "", "", "" ],
								"fontname" : "Arial",
								"numinlets" : 1,
								"patching_rect" : [ 483.0, 196.0, 62.0, 20.0 ],
								"numoutlets" : 3,
								"restore" : [ 13.0 ],
								"saved_object_attributes" : 								{
									"parameter_enable" : 0
								}

							}

						}
, 						{
							"box" : 							{
								"maxclass" : "newobj",
								"text" : "data-handler",
								"id" : "obj-39",
								"style" : "",
								"fontsize" : 12.0,
								"outlettype" : [ "", "" ],
								"fontname" : "Arial",
								"numinlets" : 2,
								"patching_rect" : [ 751.0, 141.0, 88.0, 20.0 ],
								"numoutlets" : 2
							}

						}
, 						{
							"box" : 							{
								"maxclass" : "newobj",
								"text" : "data-handler",
								"id" : "obj-40",
								"style" : "",
								"fontsize" : 12.0,
								"outlettype" : [ "", "" ],
								"fontname" : "Arial",
								"numinlets" : 2,
								"patching_rect" : [ 440.0, 141.0, 88.0, 20.0 ],
								"numoutlets" : 2
							}

						}
, 						{
							"box" : 							{
								"maxclass" : "newobj",
								"text" : "video-handler",
								"id" : "obj-56",
								"style" : "",
								"fontsize" : 12.0,
								"outlettype" : [ "jit_matrix", "jit_matrix", "" ],
								"fontname" : "Arial",
								"numinlets" : 2,
								"patching_rect" : [ 173.0, 224.0, 85.0, 20.0 ],
								"numoutlets" : 3
							}

						}
, 						{
							"box" : 							{
								"maxclass" : "newobj",
								"text" : "data-handler",
								"id" : "obj-41",
								"style" : "",
								"fontsize" : 12.0,
								"outlettype" : [ "", "" ],
								"fontname" : "Arial",
								"numinlets" : 2,
								"patching_rect" : [ 600.0, 141.0, 88.0, 20.0 ],
								"numoutlets" : 2
							}

						}
, 						{
							"box" : 							{
								"maxclass" : "inlet",
								"id" : "obj-42",
								"style" : "",
								"outlettype" : [ "" ],
								"numinlets" : 0,
								"patching_rect" : [ 751.0, 36.0, 25.0, 25.0 ],
								"numoutlets" : 1,
								"comment" : "y range in (0. - 1.0, off/on)"
							}

						}
, 						{
							"box" : 							{
								"maxclass" : "inlet",
								"id" : "obj-43",
								"style" : "",
								"outlettype" : [ "" ],
								"numinlets" : 0,
								"patching_rect" : [ 600.0, 36.0, 25.0, 25.0 ],
								"numoutlets" : 1,
								"comment" : "x range in (0. - 1.0, off/on)"
							}

						}
, 						{
							"box" : 							{
								"maxclass" : "inlet",
								"id" : "obj-44",
								"style" : "",
								"outlettype" : [ "" ],
								"numinlets" : 0,
								"patching_rect" : [ 440.0, 39.0, 25.0, 25.0 ],
								"numoutlets" : 1,
								"comment" : "probability in (0. - 1.0, off/on)"
							}

						}
, 						{
							"box" : 							{
								"maxclass" : "inlet",
								"id" : "obj-45",
								"style" : "",
								"outlettype" : [ "jit_matrix" ],
								"numinlets" : 0,
								"patching_rect" : [ 173.0, 39.0, 25.0, 25.0 ],
								"numoutlets" : 1,
								"comment" : "video in. 0/1 (integer) bypasses/enables processing. 'off' disables input and outputs black frames, 'on' enables input."
							}

						}
, 						{
							"box" : 							{
								"maxclass" : "newobj",
								"text" : "scale 0. 100. 0. 480.",
								"id" : "obj-20",
								"style" : "",
								"fontsize" : 12.0,
								"outlettype" : [ "" ],
								"fontname" : "Arial",
								"numinlets" : 6,
								"patching_rect" : [ 751.0, 369.0, 119.0, 20.0 ],
								"numoutlets" : 1
							}

						}
, 						{
							"box" : 							{
								"maxclass" : "newobj",
								"text" : "scale 0. 100. 0. 640.",
								"id" : "obj-19",
								"style" : "",
								"fontsize" : 12.0,
								"outlettype" : [ "" ],
								"fontname" : "Arial",
								"numinlets" : 6,
								"patching_rect" : [ 600.0, 369.0, 119.0, 20.0 ],
								"numoutlets" : 1
							}

						}
, 						{
							"box" : 							{
								"maxclass" : "message",
								"text" : "prob $1",
								"id" : "obj-29",
								"style" : "",
								"fontsize" : 11.595187,
								"outlettype" : [ "" ],
								"fontname" : "Arial",
								"numinlets" : 2,
								"patching_rect" : [ 440.0, 397.684204, 48.0, 17.0 ],
								"numoutlets" : 1
							}

						}
, 						{
							"box" : 							{
								"maxclass" : "message",
								"text" : "y_range $1",
								"id" : "obj-30",
								"style" : "",
								"fontsize" : 11.595187,
								"outlettype" : [ "" ],
								"fontname" : "Arial",
								"numinlets" : 2,
								"patching_rect" : [ 751.0, 396.5, 67.0, 17.0 ],
								"numoutlets" : 1
							}

						}
, 						{
							"box" : 							{
								"maxclass" : "message",
								"text" : "x_range $1",
								"id" : "obj-31",
								"style" : "",
								"fontsize" : 11.595187,
								"outlettype" : [ "" ],
								"fontname" : "Arial",
								"numinlets" : 2,
								"patching_rect" : [ 600.0, 396.5, 67.0, 17.0 ],
								"numoutlets" : 1
							}

						}
, 						{
							"box" : 							{
								"maxclass" : "newobj",
								"text" : "jit.sprinkle",
								"id" : "obj-32",
								"style" : "",
								"fontsize" : 11.595187,
								"outlettype" : [ "jit_matrix", "" ],
								"fontname" : "Arial",
								"numinlets" : 1,
								"patching_rect" : [ 203.0, 493.0, 62.0, 19.0 ],
								"numoutlets" : 2
							}

						}
, 						{
							"box" : 							{
								"maxclass" : "outlet",
								"id" : "obj-14",
								"style" : "",
								"numinlets" : 1,
								"patching_rect" : [ 204.0, 715.0, 25.0, 25.0 ],
								"numoutlets" : 0,
								"comment" : "video out"
							}

						}
, 						{
							"box" : 							{
								"maxclass" : "live.toggle",
								"hint" : "Data received in this inlet sets the value for the x range control.",
								"varname" : "pictctrl[6]",
								"id" : "obj-46",
								"parameter_enable" : 1,
								"rounded" : 15.0,
								"outlettype" : [ "" ],
								"bgoncolor" : [ 0.184, 0.443, 0.259, 1.0 ],
								"ignoreclick" : 1,
								"bordercolor" : [ 0.184, 0.443, 0.259, 1.0 ],
								"activebgcolor" : [ 0.1, 0.1, 0.1, 1.0 ],
								"presentation_rect" : [ 117.0, 3.0, 9.742592, 9.742592 ],
								"numinlets" : 1,
								"activebgoncolor" : [ 0.184, 0.443, 0.259, 1.0 ],
								"focusbordercolor" : [ 0.184, 0.443, 0.259, 1.0 ],
								"bgcolor" : [ 0.1, 0.1, 0.1, 1.0 ],
								"patching_rect" : [ 719.0, 141.0, 15.0, 15.0 ],
								"presentation" : 1,
								"numoutlets" : 1,
								"saved_attribute_attributes" : 								{
									"valueof" : 									{
										"parameter_longname" : "pictctrl[6]",
										"parameter_shortname" : "pictctrl[1]",
										"parameter_type" : 2,
										"parameter_mmax" : 1.0,
										"parameter_enum" : [ "off", "on" ],
										"parameter_initial_enable" : 1,
										"parameter_initial" : [ 1 ]
									}

								}

							}

						}
, 						{
							"box" : 							{
								"maxclass" : "live.toggle",
								"hint" : "Data received in this inlet sets the value for the y range control.",
								"varname" : "pictctrl[7]",
								"id" : "obj-47",
								"parameter_enable" : 1,
								"rounded" : 15.0,
								"outlettype" : [ "" ],
								"bgoncolor" : [ 0.184, 0.443, 0.259, 1.0 ],
								"ignoreclick" : 1,
								"bordercolor" : [ 0.184, 0.443, 0.259, 1.0 ],
								"activebgcolor" : [ 0.1, 0.1, 0.1, 1.0 ],
								"presentation_rect" : [ 173.0, 3.0, 9.742592, 9.742592 ],
								"numinlets" : 1,
								"activebgoncolor" : [ 0.184, 0.443, 0.259, 1.0 ],
								"focusbordercolor" : [ 0.184, 0.443, 0.259, 1.0 ],
								"bgcolor" : [ 0.1, 0.1, 0.1, 1.0 ],
								"patching_rect" : [ 867.0, 141.0, 15.0, 15.0 ],
								"presentation" : 1,
								"numoutlets" : 1,
								"saved_attribute_attributes" : 								{
									"valueof" : 									{
										"parameter_longname" : "pictctrl[3]",
										"parameter_shortname" : "pictctrl[1]",
										"parameter_type" : 2,
										"parameter_mmax" : 1.0,
										"parameter_enum" : [ "off", "on" ],
										"parameter_initial_enable" : 1,
										"parameter_initial" : [ 1 ]
									}

								}

							}

						}
, 						{
							"box" : 							{
								"maxclass" : "live.toggle",
								"hint" : "Data received in this inlet sets the value for the probability control.",
								"varname" : "pictctrl[5]",
								"id" : "obj-48",
								"parameter_enable" : 1,
								"rounded" : 15.0,
								"outlettype" : [ "" ],
								"bgoncolor" : [ 0.184, 0.443, 0.259, 1.0 ],
								"ignoreclick" : 1,
								"bordercolor" : [ 0.184, 0.443, 0.259, 1.0 ],
								"activebgcolor" : [ 0.1, 0.1, 0.1, 1.0 ],
								"presentation_rect" : [ 61.0, 3.0, 9.742592, 9.742592 ],
								"numinlets" : 1,
								"activebgoncolor" : [ 0.184, 0.443, 0.259, 1.0 ],
								"focusbordercolor" : [ 0.184, 0.443, 0.259, 1.0 ],
								"bgcolor" : [ 0.1, 0.1, 0.1, 1.0 ],
								"patching_rect" : [ 552.0, 141.0, 15.0, 15.0 ],
								"presentation" : 1,
								"numoutlets" : 1,
								"saved_attribute_attributes" : 								{
									"valueof" : 									{
										"parameter_longname" : "pictctrl[8]",
										"parameter_shortname" : "pictctrl[1]",
										"parameter_type" : 2,
										"parameter_mmax" : 1.0,
										"parameter_enum" : [ "off", "on" ],
										"parameter_initial_enable" : 1,
										"parameter_initial" : [ 1 ]
									}

								}

							}

						}
, 						{
							"box" : 							{
								"maxclass" : "live.dial",
								"hint" : "Sets the percentage of the y (vertical) range over which a pixel will be displaced from its original position.",
								"varname" : "control[6]",
								"id" : "obj-50",
								"parameter_enable" : 1,
								"outlettype" : [ "", "float" ],
								"activeneedlecolor" : [ 1.0, 1.0, 1.0, 0.7 ],
								"presentation_rect" : [ 123.474808, 50.216515, 60.0, 47.0 ],
								"numinlets" : 1,
								"patching_rect" : [ 751.0, 274.069458, 44.0, 47.0 ],
								"textcolor" : [ 1.0, 1.0, 1.0, 0.7 ],
								"presentation" : 1,
								"numoutlets" : 2,
								"activedialcolor" : [ 0.184, 0.741, 0.0, 1.0 ],
								"saved_attribute_attributes" : 								{
									"valueof" : 									{
										"parameter_longname" : "y range",
										"parameter_shortname" : "y range",
										"parameter_type" : 1,
										"parameter_mmax" : 100.0,
										"parameter_initial_enable" : 1,
										"parameter_initial" : [ 0.6 ],
										"parameter_unitstyle" : 5
									}

								}

							}

						}
, 						{
							"box" : 							{
								"maxclass" : "live.dial",
								"hint" : "Sets the percentage of the x (horizontal) range over which a pixel will be displaced from its original position.",
								"varname" : "control[4]",
								"id" : "obj-37",
								"parameter_enable" : 1,
								"outlettype" : [ "", "float" ],
								"activeneedlecolor" : [ 1.0, 1.0, 1.0, 0.7 ],
								"presentation_rect" : [ 63.474808, 50.216515, 60.0, 47.0 ],
								"numinlets" : 1,
								"patching_rect" : [ 600.0, 274.069458, 44.0, 47.0 ],
								"textcolor" : [ 1.0, 1.0, 1.0, 0.7 ],
								"presentation" : 1,
								"numoutlets" : 2,
								"activedialcolor" : [ 0.184, 0.741, 0.0, 1.0 ],
								"saved_attribute_attributes" : 								{
									"valueof" : 									{
										"parameter_longname" : "x range",
										"parameter_shortname" : "x range",
										"parameter_type" : 1,
										"parameter_mmax" : 100.0,
										"parameter_initial_enable" : 1,
										"parameter_initial" : [ 0.6 ],
										"parameter_unitstyle" : 5
									}

								}

							}

						}
, 						{
							"box" : 							{
								"maxclass" : "live.dial",
								"hint" : "Sets the probability of a pixel being fogged (displaced).",
								"varname" : "control[3]",
								"id" : "obj-36",
								"parameter_enable" : 1,
								"outlettype" : [ "", "float" ],
								"activeneedlecolor" : [ 1.0, 1.0, 1.0, 0.7 ],
								"presentation_rect" : [ 3.474808, 50.216515, 60.0, 47.0 ],
								"numinlets" : 1,
								"patching_rect" : [ 440.0, 274.069458, 44.0, 47.0 ],
								"textcolor" : [ 1.0, 1.0, 1.0, 0.7 ],
								"presentation" : 1,
								"numoutlets" : 2,
								"activedialcolor" : [ 0.184, 0.741, 0.0, 1.0 ],
								"saved_attribute_attributes" : 								{
									"valueof" : 									{
										"parameter_longname" : "probability",
										"parameter_shortname" : "probability",
										"parameter_type" : 1,
										"parameter_mmax" : 100.0,
										"parameter_initial_enable" : 1,
										"parameter_initial" : [ 0.6 ],
										"parameter_unitstyle" : 5
									}

								}

							}

						}
, 						{
							"box" : 							{
								"maxclass" : "comment",
								"hint" : "Video output",
								"text" : "Video",
								"id" : "obj-2",
								"style" : "",
								"fontsize" : 9.0,
								"presentation_rect" : [ 3.474808, 110.0, 35.0, 17.0 ],
								"fontname" : "Arial Bold",
								"numinlets" : 1,
								"patching_rect" : [ 34.109558, 179.498413, 41.0, 17.0 ],
								"textcolor" : [ 1.0, 1.0, 1.0, 1.0 ],
								"presentation" : 1,
								"numoutlets" : 0
							}

						}
, 						{
							"box" : 							{
								"maxclass" : "comment",
								"hint" : "Video input",
								"text" : "Video",
								"id" : "obj-33",
								"style" : "",
								"fontsize" : 9.0,
								"presentation_rect" : [ 3.474808, 0.0, 35.0, 17.0 ],
								"fontname" : "Arial Bold",
								"numinlets" : 1,
								"patching_rect" : [ 34.109558, 52.863525, 41.0, 17.0 ],
								"textcolor" : [ 1.0, 1.0, 1.0, 1.0 ],
								"presentation" : 1,
								"numoutlets" : 0
							}

						}
, 						{
							"box" : 							{
								"maxclass" : "panel",
								"id" : "obj-109",
								"rounded" : 0,
								"style" : "",
								"presentation_rect" : [ 0.474808, 16.0, 437.268768, 19.0 ],
								"numinlets" : 1,
								"patching_rect" : [ 22.609558, 111.170532, 64.0, 64.0 ],
								"presentation" : 1,
								"numoutlets" : 0,
								"mode" : 0,
								"angle" : 0.0,
								"bgcolor" : [ 0.184, 0.443, 0.259, 1.0 ],
								"proportion" : 0.39
							}

						}
, 						{
							"box" : 							{
								"maxclass" : "panel",
								"id" : "obj-110",
								"rounded" : 0,
								"style" : "",
								"presentation_rect" : [ 0.474808, 0.0, 437.268768, 17.0 ],
								"numinlets" : 1,
								"patching_rect" : [ 22.609558, 43.437531, 64.0, 64.0 ],
								"presentation" : 1,
								"numoutlets" : 0,
								"mode" : 0,
								"angle" : 0.0,
								"bgcolor" : [ 0.0, 0.0, 0.0, 1.0 ],
								"proportion" : 0.39
							}

						}
, 						{
							"box" : 							{
								"maxclass" : "panel",
								"id" : "obj-111",
								"rounded" : 0,
								"style" : "",
								"presentation_rect" : [ 0.474808, 110.0, 437.268768, 35.433025 ],
								"numinlets" : 1,
								"patching_rect" : [ 22.609558, 325.0, 64.0, 64.0 ],
								"presentation" : 1,
								"numoutlets" : 0,
								"mode" : 0,
								"angle" : 0.0,
								"bgcolor" : [ 0.0, 0.0, 0.0, 1.0 ],
								"proportion" : 0.39
							}

						}
, 						{
							"box" : 							{
								"maxclass" : "panel",
								"id" : "obj-112",
								"rounded" : 0,
								"style" : "",
								"presentation_rect" : [ 0.474808, 34.0, 437.268768, 111.433029 ],
								"numinlets" : 1,
								"patching_rect" : [ 22.609558, 253.430542, 64.0, 64.0 ],
								"presentation" : 1,
								"numoutlets" : 0,
								"mode" : 0,
								"angle" : 0.0,
								"bgcolor" : [ 0.137255, 0.145098, 0.160784, 0.65 ],
								"proportion" : 0.39
							}

						}
, 						{
							"box" : 							{
								"maxclass" : "panel",
								"id" : "obj-113",
								"style" : "",
								"presentation_rect" : [ 0.474808, 16.0, 437.268768, 129.433029 ],
								"numinlets" : 1,
								"patching_rect" : [ 22.609558, 180.928955, 64.0, 64.0 ],
								"presentation" : 1,
								"numoutlets" : 0,
								"mode" : 0,
								"angle" : 0.0,
								"bgcolor" : [ 0.367404, 0.389405, 0.430238, 1.0 ],
								"proportion" : 0.39
							}

						}
 ],
					"lines" : [ 						{
							"patchline" : 							{
								"source" : [ "obj-9", 0 ],
								"destination" : [ "obj-10", 0 ],
								"hidden" : 0,
								"disabled" : 0
							}

						}
, 						{
							"patchline" : 							{
								"source" : [ "obj-8", 0 ],
								"destination" : [ "obj-12", 0 ],
								"hidden" : 0,
								"disabled" : 0
							}

						}
, 						{
							"patchline" : 							{
								"source" : [ "obj-7", 1 ],
								"destination" : [ "obj-37", 0 ],
								"hidden" : 0,
								"disabled" : 0
							}

						}
, 						{
							"patchline" : 							{
								"source" : [ "obj-6", 1 ],
								"destination" : [ "obj-36", 0 ],
								"hidden" : 0,
								"disabled" : 0
							}

						}
, 						{
							"patchline" : 							{
								"source" : [ "obj-56", 1 ],
								"destination" : [ "obj-32", 0 ],
								"hidden" : 0,
								"disabled" : 0
							}

						}
, 						{
							"patchline" : 							{
								"source" : [ "obj-56", 2 ],
								"destination" : [ "obj-3", 0 ],
								"hidden" : 0,
								"disabled" : 0
							}

						}
, 						{
							"patchline" : 							{
								"source" : [ "obj-56", 0 ],
								"destination" : [ "obj-14", 0 ],
								"hidden" : 0,
								"disabled" : 0
							}

						}
, 						{
							"patchline" : 							{
								"source" : [ "obj-54", 0 ],
								"destination" : [ "obj-50", 0 ],
								"hidden" : 0,
								"disabled" : 0
							}

						}
, 						{
							"patchline" : 							{
								"source" : [ "obj-53", 0 ],
								"destination" : [ "obj-37", 0 ],
								"hidden" : 0,
								"disabled" : 0
							}

						}
, 						{
							"patchline" : 							{
								"source" : [ "obj-52", 0 ],
								"destination" : [ "obj-36", 0 ],
								"hidden" : 0,
								"disabled" : 0
							}

						}
, 						{
							"patchline" : 							{
								"source" : [ "obj-51", 0 ],
								"destination" : [ "obj-29", 0 ],
								"hidden" : 0,
								"disabled" : 0
							}

						}
, 						{
							"patchline" : 							{
								"source" : [ "obj-50", 0 ],
								"destination" : [ "obj-20", 0 ],
								"hidden" : 0,
								"disabled" : 0
							}

						}
, 						{
							"patchline" : 							{
								"source" : [ "obj-48", 0 ],
								"destination" : [ "obj-40", 1 ],
								"hidden" : 0,
								"midpoints" : [ 561.0, 164.0, 538.25, 164.0, 538.25, 135.0, 518.5, 135.0 ],
								"disabled" : 0
							}

						}
, 						{
							"patchline" : 							{
								"source" : [ "obj-47", 0 ],
								"destination" : [ "obj-39", 1 ],
								"hidden" : 0,
								"midpoints" : [ 876.0, 164.0, 854.25, 164.0, 854.25, 135.0, 829.5, 135.0 ],
								"disabled" : 0
							}

						}
, 						{
							"patchline" : 							{
								"source" : [ "obj-46", 0 ],
								"destination" : [ "obj-41", 1 ],
								"hidden" : 0,
								"midpoints" : [ 728.0, 164.0, 703.25, 164.0, 703.25, 135.0, 678.5, 135.0 ],
								"disabled" : 0
							}

						}
, 						{
							"patchline" : 							{
								"source" : [ "obj-45", 0 ],
								"destination" : [ "obj-56", 0 ],
								"hidden" : 0,
								"disabled" : 0
							}

						}
, 						{
							"patchline" : 							{
								"source" : [ "obj-44", 0 ],
								"destination" : [ "obj-40", 0 ],
								"hidden" : 0,
								"disabled" : 0
							}

						}
, 						{
							"patchline" : 							{
								"source" : [ "obj-43", 0 ],
								"destination" : [ "obj-41", 0 ],
								"hidden" : 0,
								"disabled" : 0
							}

						}
, 						{
							"patchline" : 							{
								"source" : [ "obj-42", 0 ],
								"destination" : [ "obj-39", 0 ],
								"hidden" : 0,
								"disabled" : 0
							}

						}
, 						{
							"patchline" : 							{
								"source" : [ "obj-41", 0 ],
								"destination" : [ "obj-53", 0 ],
								"hidden" : 0,
								"disabled" : 0
							}

						}
, 						{
							"patchline" : 							{
								"source" : [ "obj-41", 1 ],
								"destination" : [ "obj-46", 0 ],
								"hidden" : 0,
								"midpoints" : [ 678.5, 169.0, 709.0, 169.0, 709.0, 130.0, 728.0, 130.0 ],
								"disabled" : 0
							}

						}
, 						{
							"patchline" : 							{
								"source" : [ "obj-40", 0 ],
								"destination" : [ "obj-52", 0 ],
								"hidden" : 0,
								"disabled" : 0
							}

						}
, 						{
							"patchline" : 							{
								"source" : [ "obj-40", 1 ],
								"destination" : [ "obj-48", 0 ],
								"hidden" : 0,
								"midpoints" : [ 518.5, 169.0, 544.0, 169.0, 544.0, 130.0, 561.0, 130.0 ],
								"disabled" : 0
							}

						}
, 						{
							"patchline" : 							{
								"source" : [ "obj-39", 0 ],
								"destination" : [ "obj-54", 0 ],
								"hidden" : 0,
								"disabled" : 0
							}

						}
, 						{
							"patchline" : 							{
								"source" : [ "obj-39", 1 ],
								"destination" : [ "obj-47", 0 ],
								"hidden" : 0,
								"midpoints" : [ 829.5, 169.0, 860.0, 169.0, 860.0, 130.0, 876.0, 130.0 ],
								"disabled" : 0
							}

						}
, 						{
							"patchline" : 							{
								"source" : [ "obj-37", 0 ],
								"destination" : [ "obj-19", 0 ],
								"hidden" : 0,
								"disabled" : 0
							}

						}
, 						{
							"patchline" : 							{
								"source" : [ "obj-36", 0 ],
								"destination" : [ "obj-51", 0 ],
								"hidden" : 0,
								"disabled" : 0
							}

						}
, 						{
							"patchline" : 							{
								"source" : [ "obj-32", 0 ],
								"destination" : [ "obj-14", 0 ],
								"hidden" : 0,
								"disabled" : 0
							}

						}
, 						{
							"patchline" : 							{
								"source" : [ "obj-31", 0 ],
								"destination" : [ "obj-32", 0 ],
								"hidden" : 0,
								"midpoints" : [ 609.5, 480.0, 212.5, 480.0 ],
								"disabled" : 0
							}

						}
, 						{
							"patchline" : 							{
								"source" : [ "obj-30", 0 ],
								"destination" : [ "obj-32", 0 ],
								"hidden" : 0,
								"midpoints" : [ 760.5, 480.0, 212.5, 480.0 ],
								"disabled" : 0
							}

						}
, 						{
							"patchline" : 							{
								"source" : [ "obj-3", 0 ],
								"destination" : [ "obj-56", 1 ],
								"hidden" : 0,
								"disabled" : 0
							}

						}
, 						{
							"patchline" : 							{
								"source" : [ "obj-29", 0 ],
								"destination" : [ "obj-32", 0 ],
								"hidden" : 0,
								"midpoints" : [ 449.5, 480.0, 212.5, 480.0 ],
								"disabled" : 0
							}

						}
, 						{
							"patchline" : 							{
								"source" : [ "obj-20", 0 ],
								"destination" : [ "obj-30", 0 ],
								"hidden" : 0,
								"disabled" : 0
							}

						}
, 						{
							"patchline" : 							{
								"source" : [ "obj-19", 0 ],
								"destination" : [ "obj-31", 0 ],
								"hidden" : 0,
								"disabled" : 0
							}

						}
, 						{
							"patchline" : 							{
								"source" : [ "obj-12", 1 ],
								"destination" : [ "obj-20", 4 ],
								"hidden" : 0,
								"midpoints" : [ 1052.5, 349.749207, 840.5, 349.749207 ],
								"disabled" : 0
							}

						}
, 						{
							"patchline" : 							{
								"source" : [ "obj-12", 0 ],
								"destination" : [ "obj-19", 4 ],
								"hidden" : 0,
								"midpoints" : [ 1010.5, 331.749207, 689.5, 331.749207 ],
								"disabled" : 0
							}

						}
, 						{
							"patchline" : 							{
								"source" : [ "obj-11", 1 ],
								"destination" : [ "obj-50", 0 ],
								"hidden" : 0,
								"disabled" : 0
							}

						}
 ]
				}

			}

		}
, 		{
			"box" : 			{
				"maxclass" : "bpatcher",
				"annotation" : "## VIZZIE video projector interface ##",
				"varname" : "projectr",
				"prototypename" : "pixl",
				"viewvisibility" : 1,
				"offset" : [ 0.0, 0.0 ],
				"lockeddragscroll" : 0,
				"clickthrough" : 0,
				"enablehscroll" : 0,
				"enablevscroll" : 0,
				"bgmode" : 1,
				"border" : 0,
				"id" : "obj-19",
				"name" : "vz.projectr.maxpat",
				"numinlets" : 2,
				"patching_rect" : [ 51.0, 905.333374, 168.0, 108.0 ],
				"numoutlets" : 0
			}

		}
, 		{
			"box" : 			{
				"maxclass" : "bpatcher",
				"annotation" : "## Grab webcam video for VIZZIE fun ##",
				"varname" : "grabbr",
				"prototypename" : "pixl",
				"viewvisibility" : 1,
				"offset" : [ 0.0, 0.0 ],
				"lockeddragscroll" : 0,
				"clickthrough" : 0,
				"enablehscroll" : 0,
				"enablevscroll" : 0,
				"bgmode" : 1,
				"border" : 0,
				"id" : "obj-17",
				"name" : "vz.grabbr.maxpat",
				"outlettype" : [ "jit_matrix" ],
				"numinlets" : 2,
				"patching_rect" : [ 260.0, 232.0, 346.0, 158.0 ],
				"numoutlets" : 1
			}

		}
 ],
	"lines" : [ 		{
			"patchline" : 			{
				"source" : [ "obj-9", 0 ],
				"destination" : [ "obj-19", 0 ],
				"hidden" : 0,
				"disabled" : 0
			}

		}
, 		{
			"patchline" : 			{
				"source" : [ "obj-71", 0 ],
				"destination" : [ "obj-39", 0 ],
				"hidden" : 0,
				"disabled" : 0
			}

		}
, 		{
			"patchline" : 			{
				"source" : [ "obj-70", 0 ],
				"destination" : [ "obj-63", 0 ],
				"hidden" : 0,
				"disabled" : 0
			}

		}
, 		{
			"patchline" : 			{
				"source" : [ "obj-70", 0 ],
				"destination" : [ "obj-20", 0 ],
				"hidden" : 0,
				"disabled" : 0
			}

		}
, 		{
			"patchline" : 			{
				"source" : [ "obj-67", 0 ],
				"destination" : [ "obj-52", 0 ],
				"hidden" : 0,
				"disabled" : 0
			}

		}
, 		{
			"patchline" : 			{
				"source" : [ "obj-63", 0 ],
				"destination" : [ "obj-71", 0 ],
				"hidden" : 0,
				"disabled" : 0
			}

		}
, 		{
			"patchline" : 			{
				"source" : [ "obj-6", 0 ],
				"destination" : [ "obj-21", 1 ],
				"hidden" : 0,
				"disabled" : 0
			}

		}
, 		{
			"patchline" : 			{
				"source" : [ "obj-52", 0 ],
				"destination" : [ "obj-1", 0 ],
				"hidden" : 0,
				"disabled" : 0
			}

		}
, 		{
			"patchline" : 			{
				"source" : [ "obj-43", 0 ],
				"destination" : [ "obj-33", 0 ],
				"hidden" : 0,
				"disabled" : 0
			}

		}
, 		{
			"patchline" : 			{
				"source" : [ "obj-43", 0 ],
				"destination" : [ "obj-32", 0 ],
				"hidden" : 0,
				"disabled" : 0
			}

		}
, 		{
			"patchline" : 			{
				"source" : [ "obj-42", 0 ],
				"destination" : [ "obj-16", 0 ],
				"hidden" : 0,
				"disabled" : 0
			}

		}
, 		{
			"patchline" : 			{
				"source" : [ "obj-40", 0 ],
				"destination" : [ "obj-12", 0 ],
				"hidden" : 0,
				"disabled" : 0
			}

		}
, 		{
			"patchline" : 			{
				"source" : [ "obj-39", 0 ],
				"destination" : [ "obj-67", 0 ],
				"hidden" : 0,
				"disabled" : 0
			}

		}
, 		{
			"patchline" : 			{
				"source" : [ "obj-38", 0 ],
				"destination" : [ "obj-14", 0 ],
				"hidden" : 0,
				"disabled" : 0
			}

		}
, 		{
			"patchline" : 			{
				"source" : [ "obj-36", 0 ],
				"destination" : [ "obj-42", 0 ],
				"hidden" : 0,
				"disabled" : 0
			}

		}
, 		{
			"patchline" : 			{
				"source" : [ "obj-35", 0 ],
				"destination" : [ "obj-40", 0 ],
				"hidden" : 0,
				"disabled" : 0
			}

		}
, 		{
			"patchline" : 			{
				"source" : [ "obj-33", 0 ],
				"destination" : [ "obj-25", 0 ],
				"hidden" : 0,
				"disabled" : 0
			}

		}
, 		{
			"patchline" : 			{
				"source" : [ "obj-32", 0 ],
				"destination" : [ "obj-25", 0 ],
				"hidden" : 0,
				"disabled" : 0
			}

		}
, 		{
			"patchline" : 			{
				"source" : [ "obj-3", 0 ],
				"destination" : [ "obj-6", 4 ],
				"hidden" : 0,
				"disabled" : 0
			}

		}
, 		{
			"patchline" : 			{
				"source" : [ "obj-28", 0 ],
				"destination" : [ "obj-30", 0 ],
				"hidden" : 0,
				"disabled" : 0
			}

		}
, 		{
			"patchline" : 			{
				"source" : [ "obj-27", 0 ],
				"destination" : [ "obj-30", 0 ],
				"hidden" : 0,
				"disabled" : 0
			}

		}
, 		{
			"patchline" : 			{
				"source" : [ "obj-23", 0 ],
				"destination" : [ "obj-38", 0 ],
				"hidden" : 0,
				"disabled" : 0
			}

		}
, 		{
			"patchline" : 			{
				"source" : [ "obj-22", 0 ],
				"destination" : [ "obj-21", 5 ],
				"hidden" : 0,
				"disabled" : 0
			}

		}
, 		{
			"patchline" : 			{
				"source" : [ "obj-21", 0 ],
				"destination" : [ "obj-9", 0 ],
				"hidden" : 0,
				"disabled" : 0
			}

		}
, 		{
			"patchline" : 			{
				"source" : [ "obj-20", 0 ],
				"destination" : [ "obj-36", 0 ],
				"hidden" : 0,
				"disabled" : 0
			}

		}
, 		{
			"patchline" : 			{
				"source" : [ "obj-20", 0 ],
				"destination" : [ "obj-35", 0 ],
				"hidden" : 0,
				"disabled" : 0
			}

		}
, 		{
			"patchline" : 			{
				"source" : [ "obj-20", 0 ],
				"destination" : [ "obj-23", 0 ],
				"hidden" : 0,
				"disabled" : 0
			}

		}
, 		{
			"patchline" : 			{
				"source" : [ "obj-17", 0 ],
				"destination" : [ "obj-21", 0 ],
				"hidden" : 0,
				"disabled" : 0
			}

		}
, 		{
			"patchline" : 			{
				"source" : [ "obj-16", 0 ],
				"destination" : [ "obj-9", 3 ],
				"hidden" : 0,
				"disabled" : 0
			}

		}
, 		{
			"patchline" : 			{
				"source" : [ "obj-14", 0 ],
				"destination" : [ "obj-9", 1 ],
				"hidden" : 0,
				"disabled" : 0
			}

		}
, 		{
			"patchline" : 			{
				"source" : [ "obj-12", 0 ],
				"destination" : [ "obj-9", 2 ],
				"hidden" : 0,
				"disabled" : 0
			}

		}
, 		{
			"patchline" : 			{
				"source" : [ "obj-10", 0 ],
				"destination" : [ "obj-21", 4 ],
				"hidden" : 0,
				"disabled" : 0
			}

		}
, 		{
			"patchline" : 			{
				"source" : [ "obj-1", 0 ],
				"destination" : [ "obj-3", 0 ],
				"hidden" : 0,
				"disabled" : 0
			}

		}
 ],
	"appversion" : 	{
		"major" : 7,
		"minor" : 3,
		"revision" : 1,
		"architecture" : "x86",
		"modernui" : 1
	}

}
