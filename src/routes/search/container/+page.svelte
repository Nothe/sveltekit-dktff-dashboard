<script>
  import { Listgroup } from 'flowbite-svelte'





  let jsonSearchResult = {
    "hits": [
        {
            "container_id": "e1eea9c9-4b7a-40c8-ad44-61c35ce8ef0d",
            "creation_date": 1651667975128,
            "current_items": [
                {
                    "sku_code": "2711832",
                    "price": {
                        "amount": 100,
                        "currency": "EUR"
                    },
                    "quantity": 2,
                    "item_status": "SHORTAGE",
                    "status_quantity": [
                        {
                            "status": "SHORTAGE",
                            "quantity": 2
                        }
                    ]
                }
            ],
            "delivery": {
                "initial_promise": {
                    "date_from": 1651881600000,
                    "date_to": 1651881600000
                },
                "current_promise": {
                    "date_from": 1651795200000,
                    "date_to": 1651795200000,
                    "time_window": {
                        "time_from": "22:00",
                        "time_to": "22:00"
                    }
                },
                "promise_shipping_date": 1651852800718,
                "carrier_code": "CC_LOG",
                "carrier_method_code": "DECATHLON_SHOP",
                "pickup_point": {
                    "id": "6d816596-d2cf-45fb-a9cd-b38817d32dd9",
                    "service_type": "SHOP"
                }
            },
            "fulfiller_container_id": "ATFFW001055579",
            "fulfiller_sub_status": "TOTAL_SHORTAGE",
            "fulfillment_type": "STORE_DELIVERY",
            "order_id": "CI-DKTFF-b8cb7bfa-2d45-49",
            "preparation_zone": {
                "name": "CAR Manheim",
                "fulfiller": "sapff",
                "external_number": "W083"
            },
            "shipping_id": "84d8d643-b593-4971-b4f5-255dc95e98f3",
            "tracking_status": "CREATED",
            "shipping_fees": {
                "amount": 0,
                "currency": "EUR"
            },
            "site_id": "dkt_ff",
            "last_indexed_date": 1652368692495,
            "objectID": "ffd9416664fce_dashboard_generated_id",
            "_highlightResult": {
                "container_id": {
                    "value": "e1eea9c9-4b7a-40c8-ad44-61c35ce8ef0d",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "creation_date": {
                    "value": "1651667975128",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "fulfiller_container_id": {
                    "value": "ATFFW001055579",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "fulfiller_sub_status": {
                    "value": "TOTAL_SHORTAGE",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "fulfillment_type": {
                    "value": "STORE_DELIVERY",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "order_id": {
                    "value": "CI-DKTFF-b8cb7bfa-2d45-49",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "preparation_zone": {
                    "name": {
                        "value": "CAR Manheim",
                        "matchLevel": "none",
                        "matchedWords": []
                    },
                    "fulfiller": {
                        "value": "sapff",
                        "matchLevel": "none",
                        "matchedWords": []
                    },
                    "external_number": {
                        "value": "W083",
                        "matchLevel": "none",
                        "matchedWords": []
                    }
                },
                "shipping_id": {
                    "value": "84d8d643-b593-4971-b4f5-255dc95e98f3",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "tracking_status": {
                    "value": "CREATED",
                    "matchLevel": "none",
                    "matchedWords": []
                }
            }
        },
        {
            "container_id": "b2ef065d-5511-4fa0-ad7d-2cdb1381673d",
            "creation_date": 1649405973926,
            "current_items": [
                {
                    "sku_code": "176498",
                    "price": {
                        "amount": 100,
                        "currency": "EUR"
                    },
                    "quantity": 1
                },
                {
                    "sku_code": "2711832",
                    "price": {
                        "amount": 100,
                        "currency": "EUR"
                    },
                    "quantity": 1
                }
            ],
            "delivery": {
                "initial_promise": {
                    "date_from": 1649635200000,
                    "date_to": 1649635200000
                },
                "current_promise": {
                    "date_from": 1649548800000,
                    "date_to": 1649548800000,
                    "time_window": {
                        "time_from": "22:00",
                        "time_to": "22:00"
                    }
                },
                "promise_shipping_date": 1649433600148,
                "carrier_code": "GEODIS_AUSTRIA",
                "carrier_method_code": "AUSTRIA_HG"
            },
            "fulfiller_container_id": "ATFFW001054207",
            "fulfillment_type": "USER_DELIVERY",
            "order_id": "CI-DKTFF-86c4d74c-cae0-468c-aa16-2754f635bc30",
            "preparation_zone": {
                "name": "CAR Manheim",
                "fulfiller": "sapff",
                "external_number": "W083"
            },
            "shipping_id": "ce405209-0f7f-41bd-8f3c-abe32087b981",
            "tracking_status": "FULFILLED",
            "parcels": [
                {
                    "tracking_number": "TRATFFW001054207001",
                    "items": [
                        {
                            "sku_code": "176498",
                            "quantity": 1
                        },
                        {
                            "sku_code": "2711832",
                            "quantity": 1
                        }
                    ]
                }
            ],
            "shipping_fees": {
                "amount": 4990000,
                "currency": "EUR"
            },
            "site_id": "dkt_ff",
            "last_indexed_date": 1652369387112,
            "objectID": "ffab024a0095d_dashboard_generated_id",
            "_highlightResult": {
                "container_id": {
                    "value": "b2ef065d-5511-4fa0-ad7d-2cdb1381673d",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "creation_date": {
                    "value": "1649405973926",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "fulfiller_container_id": {
                    "value": "ATFFW001054207",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "fulfillment_type": {
                    "value": "USER_DELIVERY",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "order_id": {
                    "value": "CI-DKTFF-86c4d74c-cae0-468c-aa16-2754f635bc30",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "preparation_zone": {
                    "name": {
                        "value": "CAR Manheim",
                        "matchLevel": "none",
                        "matchedWords": []
                    },
                    "fulfiller": {
                        "value": "sapff",
                        "matchLevel": "none",
                        "matchedWords": []
                    },
                    "external_number": {
                        "value": "W083",
                        "matchLevel": "none",
                        "matchedWords": []
                    }
                },
                "shipping_id": {
                    "value": "ce405209-0f7f-41bd-8f3c-abe32087b981",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "tracking_status": {
                    "value": "FULFILLED",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "parcels": [
                    {
                        "items": [
                            {
                                "sku_code": {
                                    "value": "176498",
                                    "matchLevel": "none",
                                    "matchedWords": []
                                }
                            },
                            {
                                "sku_code": {
                                    "value": "2711832",
                                    "matchLevel": "none",
                                    "matchedWords": []
                                }
                            }
                        ]
                    }
                ]
            }
        },
        {
            "container_id": "121d9dcb-557f-4cfe-862c-acc9800be59f",
            "creation_date": 1649230541171,
            "current_items": [
                {
                    "sku_code": "176498",
                    "price": {
                        "amount": 100,
                        "currency": "EUR"
                    },
                    "quantity": 2
                },
                {
                    "sku_code": "2711832",
                    "price": {
                        "amount": 100,
                        "currency": "EUR"
                    },
                    "quantity": 2
                }
            ],
            "delivery": {
                "initial_promise": {
                    "date_from": 1649462400000,
                    "date_to": 1649462400000
                },
                "current_promise": {
                    "date_from": 1649376000000,
                    "date_to": 1649376000000,
                    "time_window": {
                        "time_from": "22:00",
                        "time_to": "22:00"
                    }
                },
                "promise_shipping_date": 1649433600674,
                "carrier_code": "POST_AUSTRIA",
                "carrier_method_code": "POS_RELAY_AUT",
                "pickup_point": {
                    "id": "c6a3df22-c0ce-4197-894b-3758ba263132",
                    "service_type": "SHOP"
                }
            },
            "fulfiller_container_id": "ATFFW001053713",
            "fulfillment_type": "EXTERNAL_PICKUP",
            "order_id": "CI-DKTFF-fb3b92a1-8f95-4a36-adfe-83600d4b26fa",
            "preparation_zone": {
                "name": "CAR Manheim",
                "fulfiller": "sapff",
                "external_number": "W083"
            },
            "shipping_id": "1c51d8fa-f4d6-432d-a1ed-be9bf81ab0f2",
            "tracking_status": "CREATED",
            "shipping_fees": {
                "amount": 0,
                "currency": "EUR"
            },
            "site_id": "dkt_ff",
            "last_indexed_date": 1652369794011,
            "objectID": "ffa5dcaee4bce_dashboard_generated_id",
            "_highlightResult": {
                "container_id": {
                    "value": "121d9dcb-557f-4cfe-862c-acc9800be59f",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "creation_date": {
                    "value": "1649230541171",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "fulfiller_container_id": {
                    "value": "ATFFW001053713",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "fulfillment_type": {
                    "value": "EXTERNAL_PICKUP",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "order_id": {
                    "value": "CI-DKTFF-fb3b92a1-8f95-4a36-adfe-83600d4b26fa",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "preparation_zone": {
                    "name": {
                        "value": "CAR Manheim",
                        "matchLevel": "none",
                        "matchedWords": []
                    },
                    "fulfiller": {
                        "value": "sapff",
                        "matchLevel": "none",
                        "matchedWords": []
                    },
                    "external_number": {
                        "value": "W083",
                        "matchLevel": "none",
                        "matchedWords": []
                    }
                },
                "shipping_id": {
                    "value": "1c51d8fa-f4d6-432d-a1ed-be9bf81ab0f2",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "tracking_status": {
                    "value": "CREATED",
                    "matchLevel": "none",
                    "matchedWords": []
                }
            }
        },
        {
            "container_id": "f16b875b-a9c4-4d3e-af80-a2923ee991b6",
            "creation_date": 1649429309838,
            "current_items": [
                {
                    "sku_code": "2711832",
                    "price": {
                        "amount": 100,
                        "currency": "EUR"
                    },
                    "quantity": 2
                }
            ],
            "delivery": {
                "initial_promise": {
                    "date_from": 1649635200000,
                    "date_to": 1649635200000
                },
                "current_promise": {
                    "date_from": 1649721600000,
                    "date_to": 1649721600000,
                    "time_window": {
                        "time_from": "09:00",
                        "time_to": "09:00"
                    }
                },
                "promise_shipping_date": 1649696400626,
                "carrier_code": "POST_AUSTRIA",
                "carrier_method_code": "POS_RELAY_AUT",
                "pickup_point": {
                    "id": "c6a3df22-c0ce-4197-894b-3758ba263132",
                    "service_type": "SHOP"
                }
            },
            "fulfiller_container_id": "ATFFW001054347",
            "fulfillment_type": "EXTERNAL_PICKUP",
            "order_id": "CI-DKTFF-17874962-ad14-4711-8ef0-c2e813b255bc",
            "preparation_zone": {
                "name": "CAR Manheim",
                "fulfiller": "sapff",
                "external_number": "W083"
            },
            "shipping_id": "1397b510-d131-4c57-84da-333c1af4fe18",
            "tracking_status": "CREATED",
            "shipping_fees": {
                "amount": 0,
                "currency": "EUR"
            },
            "site_id": "dkt_ff",
            "last_indexed_date": 1652369333541,
            "objectID": "ff974926be02f_dashboard_generated_id",
            "_highlightResult": {
                "container_id": {
                    "value": "f16b875b-a9c4-4d3e-af80-a2923ee991b6",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "creation_date": {
                    "value": "1649429309838",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "fulfiller_container_id": {
                    "value": "ATFFW001054347",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "fulfillment_type": {
                    "value": "EXTERNAL_PICKUP",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "order_id": {
                    "value": "CI-DKTFF-17874962-ad14-4711-8ef0-c2e813b255bc",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "preparation_zone": {
                    "name": {
                        "value": "CAR Manheim",
                        "matchLevel": "none",
                        "matchedWords": []
                    },
                    "fulfiller": {
                        "value": "sapff",
                        "matchLevel": "none",
                        "matchedWords": []
                    },
                    "external_number": {
                        "value": "W083",
                        "matchLevel": "none",
                        "matchedWords": []
                    }
                },
                "shipping_id": {
                    "value": "1397b510-d131-4c57-84da-333c1af4fe18",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "tracking_status": {
                    "value": "CREATED",
                    "matchLevel": "none",
                    "matchedWords": []
                }
            }
        },
        {
            "container_id": "318dc7e7-fdd7-4bce-8132-aeb606586bff",
            "creation_date": 1639647843668,
            "delivery": {
                "initial_promise": {
                    "date_from": 1639872000000,
                    "date_to": 1639872000000
                },
                "current_promise": {
                    "date_from": 1639872000000,
                    "date_to": 1639872000000
                },
                "promise_shipping_date": 1639846800833,
                "carrier_code": "POST_AUSTRIA",
                "carrier_method_code": "POS_RELAY_AUT",
                "pickup_point": {
                    "id": "c6a3df22-c0ce-4197-894b-3758ba263132",
                    "service_type": "SHOP"
                }
            },
            "fulfiller_container_id": "ATFFW001045313",
            "fulfiller_sub_status": "TOTAL_SHORTAGE",
            "fulfillment_customer_data": [
                {
                    "name": "shipping.postcode",
                    "value": "59000"
                }
            ],
            "fulfillment_type": "EXTERNAL_PICKUP",
            "order_id": "CI-DKTFF-2b057e1a-15c3-4505-9379-cf46ca859c92",
            "preparation_zone": {
                "name": "CAR Manheim",
                "fulfiller": "sapff",
                "external_number": "W083"
            },
            "shipping_id": "184446ac-cf48-4afa-877c-6fd334970081",
            "tracking_status": "CANCELLED",
            "shipping_fees": {
                "amount": 0,
                "currency": "EUR"
            },
            "site_id": "dkt_ff",
            "objectID": "ff73b190dd0c0_dashboard_generated_id",
            "_highlightResult": {
                "container_id": {
                    "value": "318dc7e7-fdd7-4bce-8132-aeb606586bff",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "creation_date": {
                    "value": "1639647843668",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "fulfiller_container_id": {
                    "value": "ATFFW001045313",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "fulfiller_sub_status": {
                    "value": "TOTAL_SHORTAGE",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "fulfillment_type": {
                    "value": "EXTERNAL_PICKUP",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "order_id": {
                    "value": "CI-DKTFF-2b057e1a-15c3-4505-9379-cf46ca859c92",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "preparation_zone": {
                    "name": {
                        "value": "CAR Manheim",
                        "matchLevel": "none",
                        "matchedWords": []
                    },
                    "fulfiller": {
                        "value": "sapff",
                        "matchLevel": "none",
                        "matchedWords": []
                    },
                    "external_number": {
                        "value": "W083",
                        "matchLevel": "none",
                        "matchedWords": []
                    }
                },
                "shipping_id": {
                    "value": "184446ac-cf48-4afa-877c-6fd334970081",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "tracking_status": {
                    "value": "CANCELLED",
                    "matchLevel": "none",
                    "matchedWords": []
                }
            }
        },
        {
            "container_id": "cc192f58-ad78-42d2-affc-259fb8e581e6",
            "creation_date": 1649432919092,
            "delivery": {
                "initial_promise": {
                    "date_from": 1649462400000,
                    "date_to": 1649462400000
                },
                "current_promise": {
                    "date_from": 1649376000000,
                    "date_to": 1649376000000,
                    "time_window": {
                        "time_from": "22:00",
                        "time_to": "22:00"
                    }
                },
                "promise_shipping_date": 1649436519831,
                "carrier_code": "MY_SFS",
                "carrier_method_code": "POS_STD_AUT"
            },
            "fulfiller_container_id": "ATFFS000038995",
            "fulfiller_sub_status": "COMPLETED",
            "fulfillment_type": "USER_DELIVERY",
            "order_id": "CI-DKTFF-89369e94-c5b2-411e-967e-38c1817d4c10",
            "preparation_zone": {
                "name": "Store Graz",
                "fulfiller": "storesff",
                "external_number": "2055"
            },
            "shipping_id": "dade69fb-0bd2-47d2-911b-390bfd1e37e9",
            "tracking_status": "CANCELLED",
            "parcels": [
                {
                    "tracking_number": "ATFFS000038995P01"
                },
                {
                    "tracking_number": "ATFFS000038995P02"
                }
            ],
            "shipping_fees": {
                "amount": 0,
                "currency": "EUR"
            },
            "site_id": "dkt_ff",
            "last_indexed_date": 1652369312001,
            "objectID": "ff36134dade28_dashboard_generated_id",
            "_highlightResult": {
                "container_id": {
                    "value": "cc192f58-ad78-42d2-affc-259fb8e581e6",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "creation_date": {
                    "value": "1649432919092",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "fulfiller_container_id": {
                    "value": "ATFFS000038995",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "fulfiller_sub_status": {
                    "value": "COMPLETED",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "fulfillment_type": {
                    "value": "USER_DELIVERY",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "order_id": {
                    "value": "CI-DKTFF-89369e94-c5b2-411e-967e-38c1817d4c10",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "preparation_zone": {
                    "name": {
                        "value": "Store Graz",
                        "matchLevel": "none",
                        "matchedWords": []
                    },
                    "fulfiller": {
                        "value": "storesff",
                        "matchLevel": "none",
                        "matchedWords": []
                    },
                    "external_number": {
                        "value": "2055",
                        "matchLevel": "none",
                        "matchedWords": []
                    }
                },
                "shipping_id": {
                    "value": "dade69fb-0bd2-47d2-911b-390bfd1e37e9",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "tracking_status": {
                    "value": "CANCELLED",
                    "matchLevel": "none",
                    "matchedWords": []
                }
            }
        },
        {
            "container_id": "ace60c21-d3ca-4a41-adfc-e73478effa83",
            "creation_date": 1649754386478,
            "current_items": [
                {
                    "sku_code": "176498",
                    "price": {
                        "amount": 100,
                        "currency": "EUR"
                    },
                    "quantity": 1
                },
                {
                    "sku_code": "2711832",
                    "price": {
                        "amount": 100,
                        "currency": "EUR"
                    },
                    "quantity": 1
                }
            ],
            "delivery": {
                "initial_promise": {
                    "date_from": 1649980800000,
                    "date_to": 1649980800000
                },
                "current_promise": {
                    "date_from": 1649894400000,
                    "date_to": 1649894400000,
                    "time_window": {
                        "time_from": "22:00",
                        "time_to": "22:00"
                    }
                },
                "promise_shipping_date": 1649952000254,
                "carrier_code": "POST_AUSTRIA",
                "carrier_method_code": "POS_RELAY_AUT",
                "pickup_point": {
                    "id": "c6a3df22-c0ce-4197-894b-3758ba263132",
                    "service_type": "SHOP"
                }
            },
            "fulfiller_container_id": "ATFFW001054610",
            "fulfillment_type": "EXTERNAL_PICKUP",
            "order_id": "CI-DKTFF-3b8ab95b-a676-4838-a087-acad71fb8018",
            "preparation_zone": {
                "name": "CAR Manheim",
                "fulfiller": "sapff",
                "external_number": "W083"
            },
            "shipping_id": "900bb595-87d6-4231-99f5-4d7249fe804c",
            "tracking_status": "CREATED",
            "shipping_fees": {
                "amount": 0,
                "currency": "EUR"
            },
            "site_id": "dkt_ff",
            "last_indexed_date": 1652369155959,
            "objectID": "ff2d557bed58a_dashboard_generated_id",
            "_highlightResult": {
                "container_id": {
                    "value": "ace60c21-d3ca-4a41-adfc-e73478effa83",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "creation_date": {
                    "value": "1649754386478",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "fulfiller_container_id": {
                    "value": "ATFFW001054610",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "fulfillment_type": {
                    "value": "EXTERNAL_PICKUP",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "order_id": {
                    "value": "CI-DKTFF-3b8ab95b-a676-4838-a087-acad71fb8018",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "preparation_zone": {
                    "name": {
                        "value": "CAR Manheim",
                        "matchLevel": "none",
                        "matchedWords": []
                    },
                    "fulfiller": {
                        "value": "sapff",
                        "matchLevel": "none",
                        "matchedWords": []
                    },
                    "external_number": {
                        "value": "W083",
                        "matchLevel": "none",
                        "matchedWords": []
                    }
                },
                "shipping_id": {
                    "value": "900bb595-87d6-4231-99f5-4d7249fe804c",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "tracking_status": {
                    "value": "CREATED",
                    "matchLevel": "none",
                    "matchedWords": []
                }
            }
        },
        {
            "container_id": "859e4f4f-3273-45c2-8cf8-cbdae9ab755f",
            "creation_date": 1651150509799,
            "current_items": [
                {
                    "sku_code": "2463055",
                    "price": {
                        "amount": 39900000,
                        "currency": "EUR"
                    },
                    "quantity": 5
                },
                {
                    "sku_code": "2463058",
                    "price": {
                        "amount": 39900000,
                        "currency": "EUR"
                    },
                    "quantity": 5
                }
            ],
            "delivery": {
                "initial_promise": {
                    "date_from": 1651363200000,
                    "date_to": 1651363200000
                },
                "current_promise": {
                    "date_from": 1651276800000,
                    "date_to": 1651276800000,
                    "time_window": {
                        "time_from": "22:00",
                        "time_to": "22:00"
                    }
                },
                "promise_shipping_date": 1651248000926,
                "carrier_code": "GEODIS_AUSTRIA",
                "carrier_method_code": "AUSTRIA_HG"
            },
            "fulfiller_container_id": "ATFFW001055291",
            "fulfillment_type": "USER_DELIVERY",
            "order_id": "AT_PREPROD_3417",
            "preparation_zone": {
                "name": "CAR Manheim",
                "fulfiller": "sapff",
                "external_number": "W083"
            },
            "shipping_id": "4d5740c1-5be3-4563-a436-762178ee3a4a",
            "tracking_status": "FULFILLED",
            "parcels": [
                {
                    "tracking_number": "TRACKING_ATFFW001055291",
                    "items": [
                        {
                            "sku_code": "767673",
                            "quantity": 1
                        },
                        {
                            "sku_code": "767657",
                            "quantity": 1
                        }
                    ]
                }
            ],
            "shipping_fees": {
                "amount": 4990000,
                "currency": "EUR"
            },
            "site_id": "dkt_ff",
            "last_indexed_date": 1652368893546,
            "objectID": "ff2b5c57aeb7c_dashboard_generated_id",
            "_highlightResult": {
                "container_id": {
                    "value": "859e4f4f-3273-45c2-8cf8-cbdae9ab755f",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "creation_date": {
                    "value": "1651150509799",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "fulfiller_container_id": {
                    "value": "ATFFW001055291",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "fulfillment_type": {
                    "value": "USER_DELIVERY",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "order_id": {
                    "value": "AT_PREPROD_3417",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "preparation_zone": {
                    "name": {
                        "value": "CAR Manheim",
                        "matchLevel": "none",
                        "matchedWords": []
                    },
                    "fulfiller": {
                        "value": "sapff",
                        "matchLevel": "none",
                        "matchedWords": []
                    },
                    "external_number": {
                        "value": "W083",
                        "matchLevel": "none",
                        "matchedWords": []
                    }
                },
                "shipping_id": {
                    "value": "4d5740c1-5be3-4563-a436-762178ee3a4a",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "tracking_status": {
                    "value": "FULFILLED",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "parcels": [
                    {
                        "items": [
                            {
                                "sku_code": {
                                    "value": "767673",
                                    "matchLevel": "none",
                                    "matchedWords": []
                                }
                            },
                            {
                                "sku_code": {
                                    "value": "767657",
                                    "matchLevel": "none",
                                    "matchedWords": []
                                }
                            }
                        ]
                    }
                ]
            }
        },
        {
            "container_id": "7660367a-b85a-47a1-a9f1-09603b0863e7",
            "creation_date": 1639882671607,
            "current_items": [
                {
                    "sku_code": "767767",
                    "price": {
                        "amount": 100,
                        "currency": "EUR"
                    },
                    "quantity": 1
                },
                {
                    "sku_code": "2909255",
                    "price": {
                        "amount": 100,
                        "currency": "EUR"
                    },
                    "quantity": 1
                }
            ],
            "delivery": {
                "initial_promise": {
                    "date_from": 1639958400000,
                    "date_to": 1639958400000,
                    "time_window": {
                        "time_from": "10:30",
                        "time_to": "10:30"
                    }
                },
                "current_promise": {
                    "date_from": 1639958400000,
                    "date_to": 1639958400000,
                    "time_window": {
                        "time_from": "10:30",
                        "time_to": "10:30"
                    }
                },
                "promise_shipping_date": 1639987200203,
                "carrier_code": "CC_STORE",
                "carrier_method_code": "DECATHLON_SHOP",
                "pickup_point": {
                    "id": "6d816596-d2cf-45fb-a9cd-b38817d32dd9",
                    "service_type": "SHOP"
                }
            },
            "fulfiller_container_id": "ATFFS000025029",
            "fulfillment_customer_data": [
                {
                    "name": "shipping.postcode",
                    "value": "59000"
                }
            ],
            "fulfillment_type": "STORE_PICKUP",
            "order_id": "CI-DKTFF-7e004b3d-41d9-49b6-9d09-ea856ab09b3f",
            "preparation_zone": {
                "name": "z_s2055",
                "fulfiller": "storesff",
                "external_number": "2055"
            },
            "shipping_id": "db499a54-509a-4f3d-a7a4-2ecfd791a13f",
            "tracking_status": "FULFILLED",
            "shipping_fees": {
                "amount": 0,
                "currency": "EUR"
            },
            "site_id": "dkt_ff",
            "objectID": "ff1171f6cdfea_dashboard_generated_id",
            "_highlightResult": {
                "container_id": {
                    "value": "7660367a-b85a-47a1-a9f1-09603b0863e7",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "creation_date": {
                    "value": "1639882671607",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "fulfiller_container_id": {
                    "value": "ATFFS000025029",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "fulfillment_type": {
                    "value": "STORE_PICKUP",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "order_id": {
                    "value": "CI-DKTFF-7e004b3d-41d9-49b6-9d09-ea856ab09b3f",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "preparation_zone": {
                    "name": {
                        "value": "z_s2055",
                        "matchLevel": "none",
                        "matchedWords": []
                    },
                    "fulfiller": {
                        "value": "storesff",
                        "matchLevel": "none",
                        "matchedWords": []
                    },
                    "external_number": {
                        "value": "2055",
                        "matchLevel": "none",
                        "matchedWords": []
                    }
                },
                "shipping_id": {
                    "value": "db499a54-509a-4f3d-a7a4-2ecfd791a13f",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "tracking_status": {
                    "value": "FULFILLED",
                    "matchLevel": "none",
                    "matchedWords": []
                }
            }
        },
        {
            "container_id": "66f2cf4e-8f87-49f9-88b6-260131609850",
            "creation_date": 1648203315467,
            "current_items": [
                {
                    "sku_code": "383106",
                    "price": {
                        "amount": 100,
                        "currency": "EUR"
                    },
                    "quantity": 3
                }
            ],
            "delivery": {
                "initial_promise": {
                    "date_from": 1648684800000,
                    "date_to": 1649030400000
                },
                "current_promise": {
                    "date_from": 1648598400000,
                    "date_to": 1648944000000,
                    "time_window": {
                        "time_from": "22:00",
                        "time_to": "22:00"
                    }
                },
                "promise_shipping_date": 1648470600839,
                "carrier_code": "POSTNORD",
                "carrier_method_code": "PN_PUP",
                "pickup_point": {
                    "id": "1c358f0d-d917-439d-8979-6444d03dbd6a",
                    "service_type": "SHOP"
                }
            },
            "fulfiller_container_id": "SEFFW001052958",
            "fulfillment_type": "EXTERNAL_PICKUP",
            "order_id": "eb05a61d-2d49-45e3-8582-2d1f06ca14ae",
            "preparation_zone": {
                "name": "CAR-Mannheim",
                "fulfiller": "sapff",
                "external_number": "W083"
            },
            "shipping_id": "f67ba189-8e6e-4d16-85b9-9eede4c14ce7",
            "tracking_status": "FULFILLED",
            "parcels": [
                {
                    "tracking_number": "TRACKING_SEFFW001052958",
                    "items": [
                        {
                            "sku_code": "767673",
                            "quantity": 1
                        },
                        {
                            "sku_code": "767657",
                            "quantity": 1
                        }
                    ]
                }
            ],
            "shipping_fees": {
                "amount": 49000000,
                "currency": "SEK"
            },
            "site_id": "dkt_ff",
            "last_indexed_date": 1652370409072,
            "objectID": "fef26b8ae542f_dashboard_generated_id",
            "_highlightResult": {
                "container_id": {
                    "value": "66f2cf4e-8f87-49f9-88b6-260131609850",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "creation_date": {
                    "value": "1648203315467",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "fulfiller_container_id": {
                    "value": "SEFFW001052958",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "fulfillment_type": {
                    "value": "EXTERNAL_PICKUP",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "order_id": {
                    "value": "eb05a61d-2d49-45e3-8582-2d1f06ca14ae",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "preparation_zone": {
                    "name": {
                        "value": "CAR-Mannheim",
                        "matchLevel": "none",
                        "matchedWords": []
                    },
                    "fulfiller": {
                        "value": "sapff",
                        "matchLevel": "none",
                        "matchedWords": []
                    },
                    "external_number": {
                        "value": "W083",
                        "matchLevel": "none",
                        "matchedWords": []
                    }
                },
                "shipping_id": {
                    "value": "f67ba189-8e6e-4d16-85b9-9eede4c14ce7",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "tracking_status": {
                    "value": "FULFILLED",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "parcels": [
                    {
                        "items": [
                            {
                                "sku_code": {
                                    "value": "767673",
                                    "matchLevel": "none",
                                    "matchedWords": []
                                }
                            },
                            {
                                "sku_code": {
                                    "value": "767657",
                                    "matchLevel": "none",
                                    "matchedWords": []
                                }
                            }
                        ]
                    }
                ]
            }
        },
        {
            "container_id": "69a61a74-358b-4abf-8a6e-2695fcf92884",
            "creation_date": 1643963595365,
            "current_items": [
                {
                    "sku_code": "767767",
                    "price": {
                        "amount": 100,
                        "currency": "EUR"
                    },
                    "quantity": 1
                },
                {
                    "sku_code": "2410367",
                    "price": {
                        "amount": 100,
                        "currency": "EUR"
                    },
                    "quantity": 1
                }
            ],
            "delivery": {
                "initial_promise": {
                    "date_from": 1644019200000,
                    "date_to": 1644019200000
                },
                "current_promise": {
                    "date_from": 1643932800000,
                    "date_to": 1643932800000,
                    "time_window": {
                        "time_from": "23:00",
                        "time_to": "23:00"
                    }
                },
                "promise_shipping_date": 1643967195680,
                "carrier_code": "MY_SFS",
                "carrier_method_code": "POS_STD_AUT"
            },
            "fulfiller_container_id": "ATFFS000028874",
            "fulfillment_customer_data": [
                {
                    "name": "shipping.postcode",
                    "value": "59000"
                }
            ],
            "fulfillment_type": "USER_DELIVERY",
            "order_id": "CI-DKTFF-9fd6e20c-a8dd-417c-bb34-5b2742d725df",
            "preparation_zone": {
                "name": "z_s2055",
                "fulfiller": "storesff",
                "external_number": "2055"
            },
            "shipping_id": "220bac4f-db58-43c1-859c-1f1b15f04c66",
            "tracking_status": "CREATED",
            "shipping_fees": {
                "amount": 10000000,
                "currency": "EUR"
            },
            "site_id": "dkt_ff",
            "objectID": "fedc1e262d02f_dashboard_generated_id",
            "_highlightResult": {
                "container_id": {
                    "value": "69a61a74-358b-4abf-8a6e-2695fcf92884",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "creation_date": {
                    "value": "1643963595365",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "fulfiller_container_id": {
                    "value": "ATFFS000028874",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "fulfillment_type": {
                    "value": "USER_DELIVERY",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "order_id": {
                    "value": "CI-DKTFF-9fd6e20c-a8dd-417c-bb34-5b2742d725df",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "preparation_zone": {
                    "name": {
                        "value": "z_s2055",
                        "matchLevel": "none",
                        "matchedWords": []
                    },
                    "fulfiller": {
                        "value": "storesff",
                        "matchLevel": "none",
                        "matchedWords": []
                    },
                    "external_number": {
                        "value": "2055",
                        "matchLevel": "none",
                        "matchedWords": []
                    }
                },
                "shipping_id": {
                    "value": "220bac4f-db58-43c1-859c-1f1b15f04c66",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "tracking_status": {
                    "value": "CREATED",
                    "matchLevel": "none",
                    "matchedWords": []
                }
            }
        },
        {
            "container_id": "d77d10d2-2521-47bd-88b5-76405d83e2c9",
            "creation_date": 1649316116740,
            "delivery": {
                "initial_promise": {
                    "date_from": 1649548800000,
                    "date_to": 1649548800000
                },
                "current_promise": {
                    "date_from": 1649462400000,
                    "date_to": 1649462400000,
                    "time_window": {
                        "time_from": "22:00",
                        "time_to": "22:00"
                    }
                },
                "promise_shipping_date": 1649433600483,
                "carrier_code": "CC_LOG",
                "carrier_method_code": "DECATHLON_SHOP",
                "pickup_point": {
                    "id": "6d816596-d2cf-45fb-a9cd-b38817d32dd9",
                    "service_type": "SHOP"
                }
            },
            "fulfiller_container_id": "ATFFW001054038",
            "fulfillment_type": "STORE_DELIVERY",
            "order_id": "CI-DKTFF-47e98a95-f1d8-415a-8c66-e7030dd43085",
            "preparation_zone": {
                "name": "CAR Manheim",
                "fulfiller": "sapff",
                "external_number": "W083"
            },
            "shipping_id": "7d78868e-bdb6-4cfc-9a10-e5fb7ecb4031",
            "tracking_status": "CANCELLED",
            "parcels": [
                {
                    "tracking_number": "TRATFFW001054038001",
                    "items": [
                        {
                            "sku_code": "176498",
                            "quantity": 1
                        },
                        {
                            "sku_code": "2711832",
                            "quantity": 1
                        }
                    ]
                }
            ],
            "shipping_fees": {
                "amount": 0,
                "currency": "EUR"
            },
            "site_id": "dkt_ff",
            "last_indexed_date": 1652369510054,
            "objectID": "feca5b1c7b14a_dashboard_generated_id",
            "_highlightResult": {
                "container_id": {
                    "value": "d77d10d2-2521-47bd-88b5-76405d83e2c9",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "creation_date": {
                    "value": "1649316116740",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "fulfiller_container_id": {
                    "value": "ATFFW001054038",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "fulfillment_type": {
                    "value": "STORE_DELIVERY",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "order_id": {
                    "value": "CI-DKTFF-47e98a95-f1d8-415a-8c66-e7030dd43085",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "preparation_zone": {
                    "name": {
                        "value": "CAR Manheim",
                        "matchLevel": "none",
                        "matchedWords": []
                    },
                    "fulfiller": {
                        "value": "sapff",
                        "matchLevel": "none",
                        "matchedWords": []
                    },
                    "external_number": {
                        "value": "W083",
                        "matchLevel": "none",
                        "matchedWords": []
                    }
                },
                "shipping_id": {
                    "value": "7d78868e-bdb6-4cfc-9a10-e5fb7ecb4031",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "tracking_status": {
                    "value": "CANCELLED",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "parcels": [
                    {
                        "items": [
                            {
                                "sku_code": {
                                    "value": "176498",
                                    "matchLevel": "none",
                                    "matchedWords": []
                                }
                            },
                            {
                                "sku_code": {
                                    "value": "2711832",
                                    "matchLevel": "none",
                                    "matchedWords": []
                                }
                            }
                        ]
                    }
                ]
            }
        },
        {
            "container_id": "04280aa3-deb7-4da1-bbd3-829d81174298",
            "creation_date": 1639585951335,
            "delivery": {
                "initial_promise": {
                    "date_from": 1639612800000,
                    "date_to": 1639612800000,
                    "time_window": {
                        "time_from": "08:30",
                        "time_to": "08:30"
                    }
                },
                "current_promise": {
                    "date_from": 1639612800000,
                    "date_to": 1639612800000,
                    "time_window": {
                        "time_from": "08:30",
                        "time_to": "08:30"
                    }
                },
                "promise_shipping_date": 1639589552190,
                "carrier_code": "CC_STORE",
                "carrier_method_code": "DECATHLON_SHOP",
                "pickup_point": {
                    "id": "6d816596-d2cf-45fb-a9cd-b38817d32dd9",
                    "service_type": "SHOP"
                }
            },
            "fulfiller_container_id": "ATFFS000024735",
            "fulfillment_customer_data": [
                {
                    "name": "shipping.postcode",
                    "value": "59000"
                }
            ],
            "fulfillment_type": "STORE_PICKUP",
            "order_id": "CI-DKTFF-03883327-167f-496d-853a-935b13e2b6b4",
            "preparation_zone": {
                "name": "z_s2055",
                "fulfiller": "storesff",
                "external_number": "2055"
            },
            "shipping_id": "863268a3-c4b8-43b0-8f2e-7224fcbba9da",
            "tracking_status": "FULFILLED",
            "shipping_fees": {
                "amount": 0,
                "currency": "EUR"
            },
            "site_id": "dkt_ff",
            "objectID": "fec3381d1249f_dashboard_generated_id",
            "_highlightResult": {
                "container_id": {
                    "value": "04280aa3-deb7-4da1-bbd3-829d81174298",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "creation_date": {
                    "value": "1639585951335",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "fulfiller_container_id": {
                    "value": "ATFFS000024735",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "fulfillment_type": {
                    "value": "STORE_PICKUP",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "order_id": {
                    "value": "CI-DKTFF-03883327-167f-496d-853a-935b13e2b6b4",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "preparation_zone": {
                    "name": {
                        "value": "z_s2055",
                        "matchLevel": "none",
                        "matchedWords": []
                    },
                    "fulfiller": {
                        "value": "storesff",
                        "matchLevel": "none",
                        "matchedWords": []
                    },
                    "external_number": {
                        "value": "2055",
                        "matchLevel": "none",
                        "matchedWords": []
                    }
                },
                "shipping_id": {
                    "value": "863268a3-c4b8-43b0-8f2e-7224fcbba9da",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "tracking_status": {
                    "value": "FULFILLED",
                    "matchLevel": "none",
                    "matchedWords": []
                }
            }
        },
        {
            "container_id": "15435dff-56cb-4024-ad32-6e5e7c1487c2",
            "creation_date": 1643964393934,
            "current_items": [
                {
                    "sku_code": "767767",
                    "price": {
                        "amount": 100,
                        "currency": "EUR"
                    },
                    "quantity": 2
                },
                {
                    "sku_code": "2410367",
                    "price": {
                        "amount": 100,
                        "currency": "EUR"
                    },
                    "quantity": 1
                }
            ],
            "delivery": {
                "initial_promise": {
                    "date_from": 1644105600000,
                    "date_to": 1644192000000
                },
                "current_promise": {
                    "date_from": 1644019200000,
                    "date_to": 1644105600000,
                    "time_window": {
                        "time_from": "23:00",
                        "time_to": "23:00"
                    }
                },
                "promise_shipping_date": 1643967994702,
                "carrier_code": "POST_AUSTRIA",
                "carrier_method_code": "POS_STD_AUT",
                "pickup_point": {
                    "id": "5892e7d3-4c17-4fcd-879a-331ce0ab25be",
                    "service_type": "LOCKER"
                }
            },
            "fulfiller_container_id": "ATFFS000029023",
            "fulfillment_customer_data": [
                {
                    "name": "shipping.postcode",
                    "value": "59000"
                }
            ],
            "fulfillment_type": "EXTERNAL_PICKUP",
            "order_id": "CI-DKTFF-c0e7cbad-bd40-4309-a365-512f0bc2fa10",
            "preparation_zone": {
                "name": "z_s2055",
                "fulfiller": "storesff",
                "external_number": "2055"
            },
            "shipping_id": "197c77d5-9ca4-441c-a88c-aab77b6359c9",
            "tracking_status": "CREATED",
            "shipping_fees": {
                "amount": 3950000,
                "currency": "EUR"
            },
            "site_id": "dkt_ff",
            "objectID": "feb9271036054_dashboard_generated_id",
            "_highlightResult": {
                "container_id": {
                    "value": "15435dff-56cb-4024-ad32-6e5e7c1487c2",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "creation_date": {
                    "value": "1643964393934",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "fulfiller_container_id": {
                    "value": "ATFFS000029023",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "fulfillment_type": {
                    "value": "EXTERNAL_PICKUP",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "order_id": {
                    "value": "CI-DKTFF-c0e7cbad-bd40-4309-a365-512f0bc2fa10",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "preparation_zone": {
                    "name": {
                        "value": "z_s2055",
                        "matchLevel": "none",
                        "matchedWords": []
                    },
                    "fulfiller": {
                        "value": "storesff",
                        "matchLevel": "none",
                        "matchedWords": []
                    },
                    "external_number": {
                        "value": "2055",
                        "matchLevel": "none",
                        "matchedWords": []
                    }
                },
                "shipping_id": {
                    "value": "197c77d5-9ca4-441c-a88c-aab77b6359c9",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "tracking_status": {
                    "value": "CREATED",
                    "matchLevel": "none",
                    "matchedWords": []
                }
            }
        },
        {
            "container_id": "be310e2e-105c-497d-bbf7-143cbd33cb10",
            "creation_date": 1641293764705,
            "current_items": [
                {
                    "sku_code": "767767",
                    "price": {
                        "amount": 100,
                        "currency": "EUR"
                    },
                    "quantity": 2
                },
                {
                    "sku_code": "2909255",
                    "price": {
                        "amount": 100,
                        "currency": "EUR"
                    },
                    "quantity": 2
                }
            ],
            "delivery": {
                "initial_promise": {
                    "date_from": 1641254400000,
                    "date_to": 1641254400000,
                    "time_window": {
                        "time_from": "12:56",
                        "time_to": "13:56"
                    }
                },
                "current_promise": {
                    "date_from": 1641254400000,
                    "date_to": 1641254400000,
                    "time_window": {
                        "time_from": "12:56",
                        "time_to": "13:56"
                    }
                },
                "promise_shipping_date": 1641297365732,
                "carrier_code": "MY_SFS",
                "carrier_method_code": "POS_STD_AUT"
            },
            "fulfiller_container_id": "ATFFS000026561",
            "fulfillment_customer_data": [
                {
                    "name": "shipping.postcode",
                    "value": "59000"
                }
            ],
            "fulfillment_type": "USER_DELIVERY",
            "order_id": "CI-DKTFF-685a6658-8bd1-4128-8c1e-c2e39caff317",
            "preparation_zone": {
                "name": "z_s2055",
                "fulfiller": "storesff",
                "external_number": "2055"
            },
            "shipping_id": "b9ca5121-73be-468a-bb91-0061103cc487",
            "tracking_status": "CREATED",
            "shipping_fees": {
                "amount": 10000000,
                "currency": "EUR"
            },
            "site_id": "dkt_ff",
            "objectID": "fe9165905b022_dashboard_generated_id",
            "_highlightResult": {
                "container_id": {
                    "value": "be310e2e-105c-497d-bbf7-143cbd33cb10",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "creation_date": {
                    "value": "1641293764705",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "fulfiller_container_id": {
                    "value": "ATFFS000026561",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "fulfillment_type": {
                    "value": "USER_DELIVERY",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "order_id": {
                    "value": "CI-DKTFF-685a6658-8bd1-4128-8c1e-c2e39caff317",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "preparation_zone": {
                    "name": {
                        "value": "z_s2055",
                        "matchLevel": "none",
                        "matchedWords": []
                    },
                    "fulfiller": {
                        "value": "storesff",
                        "matchLevel": "none",
                        "matchedWords": []
                    },
                    "external_number": {
                        "value": "2055",
                        "matchLevel": "none",
                        "matchedWords": []
                    }
                },
                "shipping_id": {
                    "value": "b9ca5121-73be-468a-bb91-0061103cc487",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "tracking_status": {
                    "value": "CREATED",
                    "matchLevel": "none",
                    "matchedWords": []
                }
            }
        },
        {
            "container_id": "7c376b5a-fba7-4eb2-a683-aabc9fb27f15",
            "creation_date": 1649237342487,
            "current_items": [
                {
                    "sku_code": "176498",
                    "price": {
                        "amount": 100,
                        "currency": "EUR"
                    },
                    "quantity": 2
                },
                {
                    "sku_code": "2711832",
                    "price": {
                        "amount": 100,
                        "currency": "EUR"
                    },
                    "quantity": 2
                }
            ],
            "delivery": {
                "initial_promise": {
                    "date_from": 1649462400000,
                    "date_to": 1649462400000
                },
                "current_promise": {
                    "date_from": 1649376000000,
                    "date_to": 1649376000000,
                    "time_window": {
                        "time_from": "22:00",
                        "time_to": "22:00"
                    }
                },
                "promise_shipping_date": 1649347200615,
                "carrier_code": "CC_LOG",
                "carrier_method_code": "DECATHLON_SHOP",
                "pickup_point": {
                    "id": "6d816596-d2cf-45fb-a9cd-b38817d32dd9",
                    "service_type": "SHOP"
                }
            },
            "fulfiller_container_id": "ATFFW001053829",
            "fulfillment_type": "STORE_DELIVERY",
            "order_id": "CI-DKTFF-4c2adb7b-eb39-4544-8328-293cef19c1ff",
            "preparation_zone": {
                "name": "CAR Manheim",
                "fulfiller": "sapff",
                "external_number": "W083"
            },
            "shipping_id": "3539ee6b-f627-40fe-b7aa-e3df40c1c19f",
            "tracking_status": "CREATED",
            "shipping_fees": {
                "amount": 0,
                "currency": "EUR"
            },
            "site_id": "dkt_ff",
            "last_indexed_date": 1652369706633,
            "objectID": "fe3639340d419_dashboard_generated_id",
            "_highlightResult": {
                "container_id": {
                    "value": "7c376b5a-fba7-4eb2-a683-aabc9fb27f15",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "creation_date": {
                    "value": "1649237342487",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "fulfiller_container_id": {
                    "value": "ATFFW001053829",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "fulfillment_type": {
                    "value": "STORE_DELIVERY",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "order_id": {
                    "value": "CI-DKTFF-4c2adb7b-eb39-4544-8328-293cef19c1ff",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "preparation_zone": {
                    "name": {
                        "value": "CAR Manheim",
                        "matchLevel": "none",
                        "matchedWords": []
                    },
                    "fulfiller": {
                        "value": "sapff",
                        "matchLevel": "none",
                        "matchedWords": []
                    },
                    "external_number": {
                        "value": "W083",
                        "matchLevel": "none",
                        "matchedWords": []
                    }
                },
                "shipping_id": {
                    "value": "3539ee6b-f627-40fe-b7aa-e3df40c1c19f",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "tracking_status": {
                    "value": "CREATED",
                    "matchLevel": "none",
                    "matchedWords": []
                }
            }
        },
        {
            "container_id": "395ef6b8-d227-4ab7-bb95-b616b2d6599c",
            "creation_date": 1648803997723,
            "current_items": [
                {
                    "sku_code": "767767",
                    "price": {
                        "amount": 100,
                        "currency": "EUR"
                    },
                    "quantity": 1
                },
                {
                    "sku_code": "2410367",
                    "price": {
                        "amount": 100,
                        "currency": "EUR"
                    },
                    "quantity": 1
                }
            ],
            "delivery": {
                "initial_promise": {
                    "date_from": 1648857600000,
                    "date_to": 1648857600000
                },
                "current_promise": {
                    "date_from": 1648771200000,
                    "date_to": 1648771200000,
                    "time_window": {
                        "time_from": "22:00",
                        "time_to": "22:00"
                    }
                },
                "promise_shipping_date": 1648807598280,
                "carrier_code": "MY_SFS",
                "carrier_method_code": "POS_STD_AUT"
            },
            "fulfiller_container_id": "ATFFS000037363",
            "fulfiller_sub_status": "NONE",
            "fulfillment_type": "USER_DELIVERY",
            "order_id": "CI-DKTFF-e9545ccc-1196-46ce-8b3f-64ea6423c2cb",
            "preparation_zone": {
                "name": "Store Graz",
                "fulfiller": "storesff",
                "external_number": "2055"
            },
            "shipping_id": "09830f89-f7e0-4b80-934b-a7abf8c6237e",
            "tracking_status": "FULFILLED",
            "parcels": [
                {
                    "tracking_number": "CARRIER_TRACKING_1"
                },
                {
                    "tracking_number": "CARRIER_TRACKING_2"
                }
            ],
            "shipping_fees": {
                "amount": 10000000,
                "currency": "EUR"
            },
            "site_id": "dkt_ff",
            "last_indexed_date": 1652370031697,
            "objectID": "fe0a26041e476_dashboard_generated_id",
            "_highlightResult": {
                "container_id": {
                    "value": "395ef6b8-d227-4ab7-bb95-b616b2d6599c",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "creation_date": {
                    "value": "1648803997723",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "fulfiller_container_id": {
                    "value": "ATFFS000037363",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "fulfiller_sub_status": {
                    "value": "NONE",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "fulfillment_type": {
                    "value": "USER_DELIVERY",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "order_id": {
                    "value": "CI-DKTFF-e9545ccc-1196-46ce-8b3f-64ea6423c2cb",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "preparation_zone": {
                    "name": {
                        "value": "Store Graz",
                        "matchLevel": "none",
                        "matchedWords": []
                    },
                    "fulfiller": {
                        "value": "storesff",
                        "matchLevel": "none",
                        "matchedWords": []
                    },
                    "external_number": {
                        "value": "2055",
                        "matchLevel": "none",
                        "matchedWords": []
                    }
                },
                "shipping_id": {
                    "value": "09830f89-f7e0-4b80-934b-a7abf8c6237e",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "tracking_status": {
                    "value": "FULFILLED",
                    "matchLevel": "none",
                    "matchedWords": []
                }
            }
        },
        {
            "container_id": "320cefe6-8d11-4140-960c-f710d17b8588",
            "creation_date": 1649257689137,
            "delivery": {
                "initial_promise": {
                    "date_from": 1649376000000,
                    "date_to": 1649462400000
                },
                "current_promise": {
                    "date_from": 1649289600000,
                    "date_to": 1649376000000,
                    "time_window": {
                        "time_from": "22:00",
                        "time_to": "22:00"
                    }
                },
                "promise_shipping_date": 1649261295148,
                "carrier_code": "POST_AUSTRIA",
                "carrier_method_code": "POS_STD_AUT",
                "pickup_point": {
                    "id": "5892e7d3-4c17-4fcd-879a-331ce0ab25be",
                    "service_type": "LOCKER"
                }
            },
            "fulfiller_container_id": "ATFFS000038435",
            "fulfillment_type": "EXTERNAL_PICKUP",
            "order_id": "CI-DKTFF-370ab210-5eb4-46aa-9cb4-7e1429b040e5",
            "preparation_zone": {
                "name": "Store Graz",
                "fulfiller": "storesff",
                "external_number": "2055"
            },
            "shipping_id": "61d5ebf9-335a-4365-a387-2a47a81fb412",
            "tracking_status": "CANCELLED",
            "shipping_fees": {
                "amount": 0,
                "currency": "EUR"
            },
            "site_id": "dkt_ff",
            "last_indexed_date": 1652369576904,
            "objectID": "fe04c46bb0d6e_dashboard_generated_id",
            "_highlightResult": {
                "container_id": {
                    "value": "320cefe6-8d11-4140-960c-f710d17b8588",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "creation_date": {
                    "value": "1649257689137",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "fulfiller_container_id": {
                    "value": "ATFFS000038435",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "fulfillment_type": {
                    "value": "EXTERNAL_PICKUP",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "order_id": {
                    "value": "CI-DKTFF-370ab210-5eb4-46aa-9cb4-7e1429b040e5",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "preparation_zone": {
                    "name": {
                        "value": "Store Graz",
                        "matchLevel": "none",
                        "matchedWords": []
                    },
                    "fulfiller": {
                        "value": "storesff",
                        "matchLevel": "none",
                        "matchedWords": []
                    },
                    "external_number": {
                        "value": "2055",
                        "matchLevel": "none",
                        "matchedWords": []
                    }
                },
                "shipping_id": {
                    "value": "61d5ebf9-335a-4365-a387-2a47a81fb412",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "tracking_status": {
                    "value": "CANCELLED",
                    "matchLevel": "none",
                    "matchedWords": []
                }
            }
        },
        {
            "container_id": "01ecfd08-7ac4-43b0-862f-1f63ff205452",
            "creation_date": 1651667908508,
            "delivery": {
                "initial_promise": {
                    "date_from": 1651795200000,
                    "date_to": 1651881600000
                },
                "current_promise": {
                    "date_from": 1651708800000,
                    "date_to": 1651795200000,
                    "time_window": {
                        "time_from": "22:00",
                        "time_to": "22:00"
                    }
                },
                "promise_shipping_date": 1651671509961,
                "carrier_code": "POST_AUSTRIA",
                "carrier_method_code": "POS_STD_AUT",
                "pickup_point": {
                    "id": "5892e7d3-4c17-4fcd-879a-331ce0ab25be",
                    "service_type": "LOCKER"
                }
            },
            "fulfiller_container_id": "ATFFS000040179",
            "fulfillment_type": "EXTERNAL_PICKUP",
            "order_id": "CI-DKTFF-0c3c4868-eb2b-4d",
            "preparation_zone": {
                "name": "Store Graz",
                "fulfiller": "storesff",
                "external_number": "2055"
            },
            "shipping_id": "3d3969a4-2a07-4029-b03f-485b9e73b985",
            "tracking_status": "CANCELLED",
            "shipping_fees": {
                "amount": 0,
                "currency": "EUR"
            },
            "site_id": "dkt_ff",
            "last_indexed_date": 1652368730687,
            "objectID": "fdd92d31da123_dashboard_generated_id",
            "_highlightResult": {
                "container_id": {
                    "value": "01ecfd08-7ac4-43b0-862f-1f63ff205452",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "creation_date": {
                    "value": "1651667908508",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "fulfiller_container_id": {
                    "value": "ATFFS000040179",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "fulfillment_type": {
                    "value": "EXTERNAL_PICKUP",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "order_id": {
                    "value": "CI-DKTFF-0c3c4868-eb2b-4d",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "preparation_zone": {
                    "name": {
                        "value": "Store Graz",
                        "matchLevel": "none",
                        "matchedWords": []
                    },
                    "fulfiller": {
                        "value": "storesff",
                        "matchLevel": "none",
                        "matchedWords": []
                    },
                    "external_number": {
                        "value": "2055",
                        "matchLevel": "none",
                        "matchedWords": []
                    }
                },
                "shipping_id": {
                    "value": "3d3969a4-2a07-4029-b03f-485b9e73b985",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "tracking_status": {
                    "value": "CANCELLED",
                    "matchLevel": "none",
                    "matchedWords": []
                }
            }
        },
        {
            "container_id": "30067615-ed32-4656-9d5e-2201c25393cf",
            "creation_date": 1649341364643,
            "delivery": {
                "initial_promise": {
                    "date_from": 1649376000000,
                    "date_to": 1649376000000
                },
                "current_promise": {
                    "date_from": 1649289600000,
                    "date_to": 1649289600000,
                    "time_window": {
                        "time_from": "22:00",
                        "time_to": "22:00"
                    }
                },
                "promise_shipping_date": 1649344967017,
                "carrier_code": "MY_SFS",
                "carrier_method_code": "POS_STD_AUT"
            },
            "fulfiller_container_id": "ATFFS000038653",
            "fulfiller_sub_status": "PACKED",
            "fulfillment_type": "USER_DELIVERY",
            "order_id": "CI-DKTFF-e57d45ff-d93e-41a7-aefc-3d0eda5d3eb8",
            "preparation_zone": {
                "name": "Store Graz",
                "fulfiller": "storesff",
                "external_number": "2055"
            },
            "shipping_id": "56a92883-5d9f-4d90-bc4b-fa5409d0fa98",
            "tracking_status": "CANCELLED",
            "parcels": [
                {
                    "tracking_number": "ATFFS000038653P01"
                }
            ],
            "shipping_fees": {
                "amount": 0,
                "currency": "EUR"
            },
            "site_id": "dkt_ff",
            "last_indexed_date": 1652369449335,
            "objectID": "fdbb3bfa8cd56_dashboard_generated_id",
            "_highlightResult": {
                "container_id": {
                    "value": "30067615-ed32-4656-9d5e-2201c25393cf",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "creation_date": {
                    "value": "1649341364643",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "fulfiller_container_id": {
                    "value": "ATFFS000038653",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "fulfiller_sub_status": {
                    "value": "PACKED",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "fulfillment_type": {
                    "value": "USER_DELIVERY",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "order_id": {
                    "value": "CI-DKTFF-e57d45ff-d93e-41a7-aefc-3d0eda5d3eb8",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "preparation_zone": {
                    "name": {
                        "value": "Store Graz",
                        "matchLevel": "none",
                        "matchedWords": []
                    },
                    "fulfiller": {
                        "value": "storesff",
                        "matchLevel": "none",
                        "matchedWords": []
                    },
                    "external_number": {
                        "value": "2055",
                        "matchLevel": "none",
                        "matchedWords": []
                    }
                },
                "shipping_id": {
                    "value": "56a92883-5d9f-4d90-bc4b-fa5409d0fa98",
                    "matchLevel": "none",
                    "matchedWords": []
                },
                "tracking_status": {
                    "value": "CANCELLED",
                    "matchLevel": "none",
                    "matchedWords": []
                }
            }
        }
    ],
    "nbHits": 5287,
    "page": 0,
    "nbPages": 50,
    "hitsPerPage": 20,
    "exhaustiveNbHits": true,
    "exhaustive": {
        "nbHits": true
    },
    "query": "",
    "params": "",
    "renderingContent": {},
    "processingTimeMS": 1,
    "processingTimingsMS": {
        "request": {
            "roundTrip": 9
        },
        "total": 1
    },
    "serverTimeMS": 1
}


let searchResult = Object.values(jsonSearchResult);

let container_id = searchResult[0].container_id ;

console.log(searchResult[0][1].container_id);




</script>

<h1></h1>
<div > 
<p class=" text-xs">order_id : {searchResult[0][0].order_id}</p>
<p class=" text-xs">container_id : {searchResult[0][0].container_id}</p>
<p class=" text-xs">fulfiller_container_id : {searchResult[0][0].fulfiller_container_id}</p>
<p class=" text-xs">shipping_id : {searchResult[0][0].shipping_id}</p>
<p class=" text-xs">site_id : {searchResult[0][0].dkt_ff}</p>
<p class=" text-xs">creation_date : {searchResult[0][0].creation_date}</p>
<p class=" text-xs">fulfiller_container_id : {searchResult[0][0].fulfiller_container_id}</p>

  <div class=" p-4 bg-white text-gray-500 text-left rounded-md shadow-sm ">
    <h3 class="uppercase bold">current_items</h3>
    <p>sku_code : {searchResult[0][0].current_items[0].sku_code}</p>
    <p>Price : {searchResult[0][0].current_items[0].price.amount} {searchResult[0][0].current_items[0].price.currency}</p>
    <p>item_quantity : {searchResult[0][0].current_items[0].quantity}</p>
    <p>item_status : {searchResult[0][0].current_items[0].item_status}</p>
    <p>status_quantity : {searchResult[0][0].current_items[0].status_quantity[0].quantity} </p>
  </div>
</div>

<div class=" p-4 bg-white text-gray-500 text-left rounded-md shadow-sm ">
    <h3 class="uppercase bold">delivery</h3>
    <p>promise_shipping_date {searchResult[0][0].delivery.promise_shipping_date}</p>    
    <p>initial_promise : date_from {searchResult[0][0].delivery.initial_promise.date_from} / date_to {searchResult[0][0].delivery.initial_promise.date_to}</p>
    <p>current_promise : date_from {searchResult[0][0].delivery.current_promise.date_from} / date_to {searchResult[0][0].delivery.initial_promise.date_to}</p>
    <p>carrier_code : {searchResult[0][0].delivery.carrier_code}</p> 
    <p>carrier_method_code : {searchResult[0][0].delivery.carrier_method_code}</p> 

</div>


