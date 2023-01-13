GET /api/traveling_abroad_certificate/{id}/copy/
Копирование полиса

Параметры запроса

id - id заказа
Пример запроса

curl --location \
--request GET 'https://b2b.bestinsure.tech/api/traveling_abroad_certificate/89/copy/' \
--header 'Authorization: Bearer <token>' \
--header 'Content-Type: application/json' \


Пример ответа

{
  "data": {
    "amount_multiple_tariff": null,
    "amount_one_time_tariff": null,
    "available_currencies": [],
    "country": [],
    "traveling_type": "Однократная",
    "currency_type": null,
    "date_from": null,
    "date_to": null,
    "period": 0,
    "days_count": 0,
    "birth_date": null,
    "eng_first_name": null,
    "eng_last_name": null,
    "first_name": null,
    "last_name": null,
    "middle_name": null,
    "passport_series": null,
    "passport_number": null,
    "policyholderIsInsuranced": false,
    "type": null,
    "legal_entity": {
      "id": 89,
      "is_active": false,
      "is_available": true,
      "created_at": "1668434087",
      "modified_at": "1668434087",
      "organizational_legal_form": null,
      "full_organization_name": null,
      "addres": null,
      "phone_number": null,
      "additional_phone_number": null,
      "taxpayer_id": null,
      "economic_activity_type": null,
      "state_registration_number": null
    },
    "physical_entity": {
      "id": 89,
      "total_price": 0,
      "is_active": false,
      "is_available": true,
      "created_at": "1668434087",
      "modified_at": "1668434087",
      "last_name": null,
      "first_name": null,
      "middle_name": null,
      "last_name_en": null,
      "first_name_en": null,
      "birth_date": null,
      "passport_series": null,
      "passport_number": null,
      "is_insured": false,
      "medical_award": "0.00",
      "insurance_award": "0.00",
      "sports_equipment_award": "0.00",
      "accident_award": "0.00",
      "baggage_award": "0.00",
      "cancellations_award": "0.00",
      "cancellations_d_award": "0.00",
      "unforeseen_expenses_award": "0.00",
      "civil_blame_award": "0.00",
      "docking_award": "0.00",
      "failure_award": "0.00",
      "flight_delay_award": "0.00"
    },
    "start_alien": false,
    "target": [
      {
        "id": 100,
        "is_active": true,
        "is_available": true,
        "created_at": "1668434086",
        "modified_at": "1668434086",
        "competition": false,
        "target": null,
        "additional_target": null,
        "additional_target_type": null,
        "certificate": 89
      }
    ],
    "id": 89,
    "insurance_award": 0,
    "total_price": 0,
    ...
    "insured": [],
    "user": {
      "id": 1,
      "login": "zbsadmin@bestdoctor.ru",
      "is_active": true,
      "created_at": "1665567352",
      "first_name": null,
      "last_name": null,
      "middle_name": null,
      "group": "Руководитель BestDoctor",
      "client_id": null,
      "department": null
    },
    "certificate_name": "22-Rules-Type-Code-00000012",
    "product_name": "Тестовый ВЗР",
    "is_active": false,
    "is_available": true,
    "created_at": "1668434087",
    "modified_at": "1668434094",
    "usd_rate": "60.39820",
    "eur_rate": "62.15540",
    "is_template": false,
    "status": false,
    "insuring_type": "Физлицо",
    "accept_date": null,
    "traveling_abroad_rule": "Rules",
    "traveling_abroad_type": "Type",
    "traveling_abroad_code": "Code",
    "insurance_id": 12,
    "clients_comment": null,
    "medicine_franchise": 0,
    "medical_award": "0.00",
    "traveling_abroad": 4,
    "multiple_tariff": null,
    "one_time_tariff": null,
    "tariff_available": [
      {
        "id": 17,
        "name": "Программа А"
      },
      {
        "id": 18,
        "name": "Программа В"
      },
      {
        "id": 19,
        "name": "Программа В1"
      },
      {
        "id": 20,
        "name": "Программа В2"
      }
    ],
    "amount_available": []
  }
}
        ],
        "amount_available": [
            {
                "id": 511,
                "name": 30000.0
            },
            {
                "id": 516,
                "name": 35000.0
            },
            {
                "id": 521,
                "name": 40000.0
            },
            {
                "id": 526,
                "name": 50000.0
            },
            {
                "id": 531,
                "name": 70000.0
            },
            {
                "id": 536,
                "name": 80000.0
            },
            {
                "id": 541,
                "name": 100000.0
            },
            {
                "id": 546,
                "name": 150000.0
            }
        ],
        "total_price": 116921.809915,
        "available_countries": [
            {
                "id": 1,
                "name": "Abkhazia",
                "is_schengen": false
            },
            {
                "id": 4,
                "name": "Albania",
                "is_schengen": false
            },
            {
                "id": 5,
                "name": "Algeria",
                "is_schengen": false
            },
            {
                "id": 7,
                "name": "Andorra",
                "is_schengen": true
            },
            {
                "id": 6,
                "name": "Angola",
                "is_schengen": false
            },
            {
                "id": 130,
                "name": "Anguilla",
                "is_schengen": false
            },
            {
                "id": 131,
                "name": "Antarctica",
                "is_schengen": false
            },
            {
                "id": 132,
                "name": "Antigua and Barbuda",
                "is_schengen": false
            },
            {
                "id": 133,
                "name": "Argentina",
                "is_schengen": false
            },
            {
                "id": 8,
                "name": "Armenia",
                "is_schengen": false
            },
            {
                "id": 134,
                "name": "Aruba",
                "is_schengen": false
            },
            {
                "id": 129,
                "name": "Australia",
                "is_schengen": false
            },
            {
                "id": 2,
                "name": "Austria",
                "is_schengen": true
            },
            {
                "id": 3,
                "name": "Azerbaijan",
                "is_schengen": false
            },
            {
                "id": 135,
                "name": "Bahamas",
                "is_schengen": false
            },
            {
                "id": 9,
                "name": "Bahrain",
                "is_schengen": false
            },
            {
                "id": 136,
                "name": "Bangladesh",
                "is_schengen": false
            },
            {
                "id": 137,
                "name": "Barbados",
                "is_schengen": false
            },
            {
                "id": 10,
                "name": "Belarus",
                "is_schengen": false
            },
            {
                "id": 11,
                "name": "Belgium",
                "is_schengen": true
            },
            {
                "id": 138,
                "name": "Belize",
                "is_schengen": false
            },
            {
                "id": 12,
                "name": "Benin",
                "is_schengen": false
            },
            {
                "id": 139,
                "name": "Bermuda",
                "is_schengen": false
            },
            {
                "id": 140,
                "name": "Bolivia",
                "is_schengen": false
            },
            {
                "id": 141,
                "name": "Bonaire",
                "is_schengen": false
            },
            {
                "id": 14,
                "name": "Bosnia and Herzegovina",
                "is_schengen": false
            },
            {
                "id": 15,
                "name": "Botswana",
                "is_schengen": false
            },
            {
                "id": 142,
                "name": "Brazil",
                "is_schengen": false
            },
            {
                "id": 143,
                "name": "British Virgin Islands",
                "is_schengen": false
            },
            {
                "id": 144,
                "name": "Brunei",
                "is_schengen": false
            },
            {
                "id": 13,
                "name": "Bulgaria",
                "is_schengen": false
            },
            {
                "id": 16,
                "name": "Burkina Faso",
                "is_schengen": false
            },
            {
                "id": 17,
                "name": "Burundi",
                "is_schengen": false
            },
            {
                "id": 18,
                "name": "Butane",
                "is_schengen": false
            },
            {
                "id": 165,
                "name": "Cambodia",
                "is_schengen": false
            },
            {
                "id": 49,
                "name": "Cameroon",
                "is_schengen": false
            },
            {
                "id": 166,
                "name": "Canada",
                "is_schengen": false
            },
            {
                "id": 47,
                "name": "Cape Verde",
                "is_schengen": false
            },
            {
                "id": 164,
                "name": "Cayman islands",
                "is_schengen": false
            },
            {
                "id": 115,
                "name": "Central African Republic",
                "is_schengen": false
            },
            {
                "id": 116,
                "name": "Chad",
                "is_schengen": false
            },
            {
                "id": 224,
                "name": "Chile",
                "is_schengen": false
            },
            {
                "id": 54,
                "name": "China",
                "is_schengen": false
            },
            {
                "id": 168,
                "name": "Colombia",
                "is_schengen": false
            },
            {
                "id": 55,
                "name": "Comoros",
                "is_schengen": false
            },
            {
                "id": 169,
                "name": "Costa Rica",
                "is_schengen": false
            },
            {
                "id": 114,
                "name": "Croatia",
                "is_schengen": false
            },
            {
                "id": 170,
                "name": "Cuba",
                "is_schengen": false
            },
            {
                "id": 171,
                "name": "Curacao",
                "is_schengen": false
            },
            {
                "id": 52,
                "name": "Cyprus",
                "is_schengen": false
            },
            {
                "id": 118,
                "name": "Czech Republic",
                "is_schengen": true
            },
            {
                "id": 33,
                "name": "Democratic Republic of the Congo",
                "is_schengen": false
            },
            {
                "id": 32,
                "name": "Denmark",
                "is_schengen": true
            },
            {
                "id": 34,
                "name": "Djibouti",
                "is_schengen": false
            },
            {
                "id": 161,
                "name": "Dominica",
                "is_schengen": false
            },
            {
                "id": 162,
                "name": "Dominican Republic",
                "is_schengen": false
            },
            {
                "id": 150,
                "name": "East Timor",
                "is_schengen": false
            },
            {
                "id": 227,
                "name": "Ecuador",
                "is_schengen": false
            },
            {
                "id": 35,
                "name": "Egypt",
                "is_schengen": false
            },
            {
                "id": 231,
                "name": "EquatorialGuinea",
                "is_schengen": false
            },
            {
                "id": 123,
                "name": "Eritrea",
                "is_schengen": false
            },
            {
                "id": 124,
                "name": "Estonia",
                "is_schengen": true
            },
            {
                "id": 125,
                "name": "Ethiopia",
                "is_schengen": false
            },
            {
                "id": 221,
                "name": "Falkland Islands",
                "is_schengen": false
            },
            {
                "id": 111,
                "name": "Faroe islands",
                "is_schengen": false
            },
            {
                "id": 219,
                "name": "Fiji",
                "is_schengen": false
            },
            {
                "id": 112,
                "name": "Finland",
                "is_schengen": true
            },
            {
                "id": 113,
                "name": "France",
                "is_schengen": true
            },
            {
                "id": 223,
                "name": "French polynesia",
                "is_schengen": false
            },
            {
                "id": 22,
                "name": "Gabon",
                "is_schengen": false
            },
            {
                "id": 23,
                "name": "Gambia",
                "is_schengen": false
            },
            {
                "id": 31,
                "name": "Georgia",
                "is_schengen": false
            },
            {
                "id": 27,
                "name": "Germany",
                "is_schengen": true
            },
            {
                "id": 24,
                "name": "Ghana",
                "is_schengen": false
            },
            {
                "id": 29,
                "name": "Gibraltar",
                "is_schengen": false
            },
            {
                "id": 20,
                "name": "Great Britain",
                "is_schengen": false
            },
            {
                "id": 30,
                "name": "Greece",
                "is_schengen": true
            },
            {
                "id": 159,
                "name": "Greenland",
                "is_schengen": false
            },
            {
                "id": 158,
                "name": "Grenada",
                "is_schengen": false
            },
            {
                "id": 154,
                "name": "Guadeloupe",
                "is_schengen": false
            },
            {
                "id": 160,
                "name": "Guam",
                "is_schengen": false
            },
            {
                "id": 155,
                "name": "Guatemala",
                "is_schengen": false
            },
            {
                "id": 28,
                "name": "Guernsey",
                "is_schengen": false
            },
            {
                "id": 25,
                "name": "Guinea",
                "is_schengen": false
            },
            {
                "id": 26,
                "name": "Guinea-Bissau",
                "is_schengen": false
            },
            {
                "id": 153,
                "name": "Guyana",
                "is_schengen": false
            },
            {
                "id": 152,
                "name": "Haiti",
                "is_schengen": false
            },
            {
                "id": 156,
                "name": "Honduras",
                "is_schengen": false
            },
            {
                "id": 233,
                "name": "HongKong",
                "is_schengen": false
            },
            {
                "id": 21,
                "name": "Hungary",
                "is_schengen": true
            },
            {
                "id": 44,
                "name": "Iceland",
                "is_schengen": true
            },
            {
                "id": 39,
                "name": "India",
                "is_schengen": false
            },
            {
                "id": 163,
                "name": "Indonesia",
                "is_schengen": false
            },
            {
                "id": 42,
                "name": "Iran",
                "is_schengen": false
            },
            {
                "id": 41,
                "name": "Iraq",
                "is_schengen": false
            },
            {
                "id": 43,
                "name": "Ireland",
                "is_schengen": false
            },
            {
                "id": 38,
                "name": "Israel",
                "is_schengen": false
            },
            {
                "id": 46,
                "name": "Italy",
                "is_schengen": true
            },
            {
                "id": 57,
                "name": "Ivory Coast",
                "is_schengen": false
            },
            {
                "id": 228,
                "name": "Jamaica",
                "is_schengen": false
            },
            {
                "id": 229,
                "name": "Jan Mayen",
                "is_schengen": false
            },
            {
                "id": 230,
                "name": "Japan",
                "is_schengen": false
            },
            {
                "id": 40,
                "name": "Jordan",
                "is_schengen": false
            },
            {
                "id": 48,
                "name": "Kazakhstan",
                "is_schengen": false
            },
            {
                "id": 51,
                "name": "Kenya",
                "is_schengen": false
            },
            {
                "id": 167,
                "name": "Kiribati",
                "is_schengen": false
            },
            {
                "id": 56,
                "name": "Kosovo",
                "is_schengen": false
            },
            {
                "id": 58,
                "name": "Kuwait",
                "is_schengen": false
            },
            {
                "id": 53,
                "name": "Kyrgyzstan",
                "is_schengen": false
            },
            {
                "id": 172,
                "name": "Laos",
                "is_schengen": false
            },
            {
                "id": 59,
                "name": "Latvia",
                "is_schengen": true
            },
            {
                "id": 62,
                "name": "Lebanon",
                "is_schengen": false
            },
            {
                "id": 60,
                "name": "Lesotho",
                "is_schengen": false
            },
            {
                "id": 61,
                "name": "Liberia",
                "is_schengen": false
            },
            {
                "id": 64,
                "name": "Liechtenstein",
                "is_schengen": true
            },
            {
                "id": 63,
                "name": "Lithuania",
                "is_schengen": true
            },
            {
                "id": 65,
                "name": "Luxembourg",
                "is_schengen": true
            },
            {
                "id": 175,
                "name": "Macau",
                "is_schengen": false
            },
            {
                "id": 67,
                "name": "Macedonia",
                "is_schengen": false
            },
            {
                "id": 174,
                "name": "Madagascar",
                "is_schengen": false
            },
            {
                "id": 68,
                "name": "Malawi",
                "is_schengen": false
            },
            {
                "id": 176,
                "name": "Malaysia",
                "is_schengen": false
            },
            {
                "id": 69,
                "name": "Mali",
                "is_schengen": false
            },
            {
                "id": 70,
                "name": "Malta",
                "is_schengen": true
            },
            {
                "id": 179,
                "name": "Marshall Islands",
                "is_schengen": false
            },
            {
                "id": 178,
                "name": "Martinique",
                "is_schengen": false
            },
            {
                "id": 66,
                "name": "Mauritania",
                "is_schengen": false
            },
            {
                "id": 173,
                "name": "Mauritius",
                "is_schengen": false
            },
            {
                "id": 180,
                "name": "Mexico",
                "is_schengen": false
            },
            {
                "id": 181,
                "name": "Micronesia",
                "is_schengen": false
            },
            {
                "id": 73,
                "name": "Moldova",
                "is_schengen": false
            },
            {
                "id": 74,
                "name": "Monaco",
                "is_schengen": false
            },
            {
                "id": 75,
                "name": "Mongolia",
                "is_schengen": false
            },
            {
                "id": 117,
                "name": "Montenegro",
                "is_schengen": false
            },
            {
                "id": 182,
                "name": "Montserat",
                "is_schengen": false
            },
            {
                "id": 71,
                "name": "Morocco",
                "is_schengen": false
            },
            {
                "id": 72,
                "name": "Mozambique",
                "is_schengen": false
            },
            {
                "id": 183,
                "name": "Myanmar",
                "is_schengen": false
            },
            {
                "id": 76,
                "name": "Namibia",
                "is_schengen": false
            },
            {
                "id": 184,
                "name": "Nauru",
                "is_schengen": false
            },
            {
                "id": 77,
                "name": "Nepal",
                "is_schengen": false
            },
            {
                "id": 79,
                "name": "Netherlands",
                "is_schengen": true
            },
            {
                "id": 185,
                "name": "Netherlands Antilles",
                "is_schengen": false
            },
            {
                "id": 188,
                "name": "New Caledonia",
                "is_schengen": false
            },
            {
                "id": 187,
                "name": "New Zealand",
                "is_schengen": false
            },
            {
                "id": 186,
                "name": "Nicaragua",
                "is_schengen": false
            },
            {
                "id": 78,
                "name": "Nigeria",
                "is_schengen": false
            },
            {
                "id": 94,
                "name": "North Korea",
                "is_schengen": false
            },
            {
                "id": 200,
                "name": "Northern Mariana Islands",
                "is_schengen": false
            },
            {
                "id": 80,
                "name": "Norway",
                "is_schengen": true
            },
            {
                "id": 82,
                "name": "Oman",
                "is_schengen": false
            },
            {
                "id": 83,
                "name": "Pakistan",
                "is_schengen": false
            },
            {
                "id": 189,
                "name": "Palau",
                "is_schengen": false
            },
            {
                "id": 190,
                "name": "Panama",
                "is_schengen": false
            },
            {
                "id": 234,
                "name": "Papua NewGuinea",
                "is_schengen": false
            },
            {
                "id": 192,
                "name": "Paraguay",
                "is_schengen": false
            },
            {
                "id": 193,
                "name": "Peru",
                "is_schengen": false
            },
            {
                "id": 220,
                "name": "Philippines",
                "is_schengen": false
            },
            {
                "id": 84,
                "name": "Poland",
                "is_schengen": true
            },
            {
                "id": 85,
                "name": "Portugal",
                "is_schengen": true
            },
            {
                "id": 194,
                "name": "Puerto Rico",
                "is_schengen": false
            },
            {
                "id": 50,
                "name": "Qatar",
                "is_schengen": false
            },
            {
                "id": 177,
                "name": "Republic of Maldives",
                "is_schengen": false
            },
            {
                "id": 87,
                "name": "Republic of Niger",
                "is_schengen": false
            },
            {
                "id": 86,
                "name": "Republic of the Congo",
                "is_schengen": false
            },
            {
                "id": 195,
                "name": "Reunion",
                "is_schengen": false
            },
            {
                "id": 90,
                "name": "Romania",
                "is_schengen": false
            },
            {
                "id": 88,
                "name": "Russian Federation",
                "is_schengen": false
            },
            {
                "id": 89,
                "name": "Rwanda",
                "is_schengen": false
            },
            {
                "id": 121,
                "name": "SCHENGEN",
                "is_schengen": false
            },
            {
                "id": 196,
                "name": "Saba",
                "is_schengen": false
            },
            {
                "id": 206,
                "name": "Saint Kitts and Nevis",
                "is_schengen": false
            },
            {
                "id": 207,
                "name": "Saint Lucia",
                "is_schengen": false
            },
            {
                "id": 203,
                "name": "Saint Martin",
                "is_schengen": false
            },
            {
                "id": 204,
                "name": "Saint Pierre and Miquelon",
                "is_schengen": false
            },
            {
                "id": 236,
                "name": "Saint Vincent andthe Grenadines",
                "is_schengen": false
            },
            {
                "id": 235,
                "name": "SaintBarthélemy",
                "is_schengen": false
            },
            {
                "id": 197,
                "name": "Salvador",
                "is_schengen": false
            },
            {
                "id": 198,
                "name": "Samoa",
                "is_schengen": false
            },
            {
                "id": 91,
                "name": "San Marino",
                "is_schengen": false
            },
            {
                "id": 199,
                "name": "Sao Tome and Principe",
                "is_schengen": false
            },
            {
                "id": 92,
                "name": "Saudi Arabia",
                "is_schengen": false
            },
            {
                "id": 95,
                "name": "Senegal",
                "is_schengen": false
            },
            {
                "id": 96,
                "name": "Serbia",
                "is_schengen": false
            },
            {
                "id": 201,
                "name": "Seychelles",
                "is_schengen": false
            },
            {
                "id": 101,
                "name": "Sierra Leone",
                "is_schengen": false
            },
            {
                "id": 208,
                "name": "Singapore",
                "is_schengen": false
            },
            {
                "id": 97,
                "name": "Slovakia",
                "is_schengen": true
            },
            {
                "id": 98,
                "name": "Slovenia",
                "is_schengen": true
            },
            {
                "id": 210,
                "name": "Solomon islands",
                "is_schengen": false
            },
            {
                "id": 99,
                "name": "Somalia",
                "is_schengen": false
            },
            {
                "id": 126,
                "name": "South Africa",
                "is_schengen": false
            },
            {
                "id": 127,
                "name": "South Korea",
                "is_schengen": false
            },
            {
                "id": 128,
                "name": "South Sudan",
                "is_schengen": false
            },
            {
                "id": 45,
                "name": "Spain",
                "is_schengen": true
            },
            {
                "id": 226,
                "name": "Sri Lanka",
                "is_schengen": false
            },
            {
                "id": 100,
                "name": "Sudan",
                "is_schengen": false
            },
            {
                "id": 211,
                "name": "Suriname",
                "is_schengen": false
            },
            {
                "id": 225,
                "name": "Svalbard",
                "is_schengen": false
            },
            {
                "id": 93,
                "name": "Swaziland",
                "is_schengen": false
            },
            {
                "id": 120,
                "name": "Sweden",
                "is_schengen": true
            },
            {
                "id": 119,
                "name": "Switzerland",
                "is_schengen": true
            },
            {
                "id": 213,
                "name": "Taiwan",
                "is_schengen": false
            },
            {
                "id": 102,
                "name": "Tajikistan",
                "is_schengen": false
            },
            {
                "id": 103,
                "name": "Tanzania",
                "is_schengen": false
            },
            {
                "id": 212,
                "name": "Thailand",
                "is_schengen": false
            },
            {
                "id": 104,
                "name": "Togo",
                "is_schengen": false
            },
            {
                "id": 215,
                "name": "Tonga",
                "is_schengen": false
            },
            {
                "id": 216,
                "name": "Trinidad and Tobago",
                "is_schengen": false
            },
            {
                "id": 105,
                "name": "Tunisia",
                "is_schengen": false
            },
            {
                "id": 107,
                "name": "Turkey",
                "is_schengen": false
            },
            {
                "id": 106,
                "name": "Turkmenistan",
                "is_schengen": false
            },
            {
                "id": 238,
                "name": "Turksand Caicos",
                "is_schengen": false
            },
            {
                "id": 217,
                "name": "Tuvalu",
                "is_schengen": false
            },
            {
                "id": 108,
                "name": "Uganda",
                "is_schengen": false
            },
            {
                "id": 110,
                "name": "Ukraine",
                "is_schengen": false
            },
            {
                "id": 81,
                "name": "United Arab Emirates",
                "is_schengen": false
            },
            {
                "id": 237,
                "name": "UnitedStates of America",
                "is_schengen": false
            },
            {
                "id": 218,
                "name": "Uruguay",
                "is_schengen": false
            },
            {
                "id": 109,
                "name": "Uzbekistan",
                "is_schengen": false
            },
            {
                "id": 145,
                "name": "Vanuatu",
                "is_schengen": false
            },
            {
                "id": 19,
                "name": "Vatican",
                "is_schengen": false
            },
            {
                "id": 146,
                "name": "Venezuela",
                "is_schengen": false
            },
            {
                "id": 151,
                "name": "Vietnam",
                "is_schengen": false
            },
            {
                "id": 149,
                "name": "Virgin Islands (US)",
                "is_schengen": false
            },
            {
                "id": 148,
                "name": "World-wide",
                "is_schengen": false
            },
            {
                "id": 232,
                "name": "World-wideexpt. Russian Federation",
                "is_schengen": false
            },
            {
                "id": 36,
                "name": "Zambia",
                "is_schengen": false
            },
            {
                "id": 37,
                "name": "Zimbabwe",
                "is_schengen": false
            },
            {
                "id": 239,
                "name": "french guiana",
                "is_schengen": false
            }
        ],
        "available_currencies": [
            "€"
        ],
        "target": [
            {
                "id": 207,
                "is_active": true,
                "is_available": true,
                "created_at": "1673601761",
                "modified_at": "1673601761",
                "competition": false,
                "target": 1,
                "additional_target": null,
                "additional_target_type": null,
                "certificate": 147
            },
            {
                "id": 208,
                "is_active": true,
                "is_available": true,
                "created_at": "1673601761",
                "modified_at": "1673601761",
                "competition": false,
                "target": 2,
                "additional_target": null,
                "additional_target_type": null,
                "certificate": 147
            },
            {
                "id": 209,
                "is_active": true,
                "is_available": true,
                "created_at": "1673601761",
                "modified_at": "1673601761",
                "competition": false,
                "target": 1,
                "additional_target": null,
                "additional_target_type": null,
                "certificate": 147
            },
            {
                "id": 210,
                "is_active": true,
                "is_available": true,
                "created_at": "1673601761",
                "modified_at": "1673601761",
                "competition": false,
                "target": 2,
                "additional_target": null,
                "additional_target_type": null,
                "certificate": 147
            }
        ],
        "country": [
            {
                "id": 1,
                "is_active": true,
                "is_available": true,
                "created_at": "1665328828",
                "modified_at": "1673442863",
                "name": "Abkhazia",
                "is_schengen": false,
                "currencies": [
                    1,
                    2,
                    3
                ],
                "groups": [
                    1,
                    3,
                    5,
                    7,
                    9,
                    11,
                    13,
                    15,
                    18,
                    34,
                    36,
                    24,
                    26,
                    28,
                    30,
                    32,
                    20,
                    22
                ]
            },
            {
                "id": 7,
                "is_active": true,
                "is_available": true,
                "created_at": "1665328828",
                "modified_at": "1673442863",
                "name": "Andorra",
                "is_schengen": true,
                "currencies": [
                    1
                ],
                "groups": [
                    1,
                    3,
                    5,
                    7,
                    9,
                    11,
                    13,
                    15,
                    18,
                    34,
                    36,
                    24,
                    26,
                    28,
                    30,
                    32,
                    20,
                    22
                ]
            },
            {
                "id": 6,
                "is_active": true,
                "is_available": true,
                "created_at": "1665328828",
                "modified_at": "1673442863",
                "name": "Angola",
                "is_schengen": false,
                "currencies": [
                    1,
                    3
                ],
                "groups": [
                    1,
                    3,
                    5,
                    7,
                    9,
                    11,
                    13,
                    15,
                    18,
                    34,
                    36,
                    24,
                    26,
                    28,
                    30,
                    32,
                    20,
                    22
                ]
            },
            {
                "id": 132,
                "is_active": true,
                "is_available": true,
                "created_at": "1665328829",
                "modified_at": "1673442863",
                "name": "Antigua and Barbuda",
                "is_schengen": false,
                "currencies": [
                    1,
                    3
                ],
                "groups": [
                    23,
                    21,
                    6,
                    8,
                    10,
                    12,
                    14,
                    16,
                    19,
                    25,
                    27,
                    29,
                    31,
                    33,
                    35,
                    2,
                    37,
                    4
                ]
            },
            {
                "id": 8,
                "is_active": true,
                "is_available": true,
                "created_at": "1665328828",
                "modified_at": "1673442863",
                "name": "Armenia",
                "is_schengen": false,
                "currencies": [
                    1,
                    3
                ],
                "groups": [
                    1,
                    3,
                    5,
                    7,
                    9,
                    11,
                    13,
                    15,
                    18,
                    34,
                    36,
                    24,
                    26,
                    28,
                    30,
                    32,
                    20,
                    22
                ]
            },
            {
                "id": 135,
                "is_active": true,
                "is_available": true,
                "created_at": "1665328829",
                "modified_at": "1673442863",
                "name": "Bahamas",
                "is_schengen": false,
                "currencies": [
                    1,
                    3
                ],
                "groups": [
                    23,
                    21,
                    6,
                    8,
                    10,
                    12,
                    14,
                    16,
                    19,
                    25,
                    27,
                    29,
                    31,
                    33,
                    35,
                    2,
                    37,
                    4
                ]
            },
            {
                "id": 35,
                "is_active": true,
                "is_available": true,
                "created_at": "1665328829",
                "modified_at": "1673442863",
                "name": "Egypt",
                "is_schengen": false,
                "currencies": [
                    1,
                    3
                ],
                "groups": [
                    1,
                    3,
                    5,
                    7,
                    9,
                    11,
                    13,
                    15,
                    18,
                    34,
                    36,
                    24,
                    26,
                    28,
                    30,
                    32,
                    20,
                    22
                ]
            },
            {
                "id": 113,
                "is_active": true,
                "is_available": true,
                "created_at": "1665328829",
                "modified_at": "1673442863",
                "name": "France",
                "is_schengen": true,
                "currencies": [
                    1
                ],
                "groups": [
                    1,
                    3,
                    5,
                    7,
                    9,
                    11,
                    13,
                    15,
                    18,
                    34,
                    36,
                    24,
                    26,
                    28,
                    30,
                    32,
                    20,
                    22
                ]
            }
        ],
        "accident": {
            "id": 167,
            "is_active": true,
            "is_available": true,
            "created_at": "1673601761",
            "modified_at": "1673601761",
            "amount": "1000.0000",
            "insurance_award": "0.80",
            "tariff": 20
        },
        "baggage": {
            "id": 167,
            "is_active": true,
            "is_available": true,
            "created_at": "1673601761",
            "modified_at": "1673601761",
            "amount": "1000.00",
            "insurance_award": "5.00",
            "tariff": 20
        },
        "sports_equipment": {
            "id": 167,
            "is_active": true,
            "is_available": true,
            "created_at": "1673601761",
            "modified_at": "1673601761",
            "amount": "2000.00",
            "insurance_award": "8.00",
            "tariff": 20
        },
        "cancellations": {
            "id": 167,
            "is_active": true,
            "is_available": true,
            "created_at": "1673601761",
            "modified_at": "1673601761",
            "amount": "10000.0000",
            "insurance_award": "600.00",
            "tariff": 57
        },
        "cancellations_d": {
            "id": 167,
            "is_active": true,
            "is_available": true,
            "created_at": "1673601761",
            "modified_at": "1673601761",
            "amount": "10000.0000",
            "insurance_award": "600.00",
            "tariff": 40
        },
        "unforeseen_expenses": {
            "id": 162,
            "is_active": true,
            "is_available": true,
            "created_at": "1673601761",
            "modified_at": "1673601761",
            "amount": "3000.0000",
            "insurance_award": "20.00",
            "tariff": 11
        },
        "failure": {
            "id": 167,
            "is_active": true,
            "is_available": true,
            "created_at": "1673601761",
            "modified_at": "1673601761",
            "amount": "10000.0000",
            "insurance_award": "600.00",
            "tariff": 30
        },
        "flight_delay": {
            "id": 167,
            "is_active": true,
            "is_available": true,
            "created_at": "1673601761",
            "modified_at": "1673601761",
            "amount": "300.00",
            "insurance_award": "10.00",
            "tariff": 20
        },
        "docking": {
            "id": 167,
            "is_active": true,
            "is_available": true,
            "created_at": "1673601761",
            "modified_at": "1673601761",
            "amount": "1000.00",
            "insurance_award": "20.00",
            "tariff": 20
        },
        "civil_blame": {
            "id": 167,
            "is_active": true,
            "is_available": true,
            "created_at": "1673601761",
            "modified_at": "1673601761",
            "amount": "20000.0000",
            "insurance_award": "2.00",
            "tariff": 20
        },
        "physical_entity": {
            "id": 158,
            "total_price": 0.0,
            "is_active": false,
            "is_available": true,
            "created_at": "1673601761",
            "modified_at": "1673601761",
            "last_name": null,
            "first_name": null,
            "middle_name": "ivanovich",
            "last_name_en": "Ivanov",
            "first_name_en": "ivan",
            "birth_date": "1960-01-01",
            "passport_series": "4500",
            "passport_number": "123123",
            "is_insured": false,
            "medical_award": "0.00",
            "insurance_award": "0.00",
            "sports_equipment_award": "0.00",
            "accident_award": "0.00",
            "baggage_award": "0.00",
            "cancellations_award": "0.00",
            "cancellations_d_award": "0.00",
            "unforeseen_expenses_award": "0.00",
            "civil_blame_award": "0.00",
            "docking_award": "0.00",
            "failure_award": "0.00",
            "flight_delay_award": "0.00"
        },
        "legal_entity": {
            "id": 167,
            "is_active": false,
            "is_available": true,
            "created_at": "1673601761",
            "modified_at": "1673601761",
            "organizational_legal_form": null,
            "full_organization_name": null,
            "addres": null,
            "phone_number": null,
            "additional_phone_number": null,
            "taxpayer_id": null,
            "economic_activity_type": null,
            "state_registration_number": null
        },
        "insured": [
            {
                "id": 115,
                "total_price": 58531.319045,
                "is_active": true,
                "is_available": true,
                "created_at": "1673601761",
                "modified_at": "1673601761",
                "last_name": null,
                "first_name": null,
                "middle_name": "pedrovich",
                "last_name_en": "petrov",
                "first_name_en": "per",
                "birth_date": "1960-01-01",
                "passport_series": null,
                "passport_number": null,
                "medical_award": "0.00",
                "insurance_award": "0.00",
                "sports_equipment_award": "0.00",
                "accident_award": "0.00",
                "baggage_award": "0.00",
                "cancellations_award": "0.00",
                "cancellations_d_award": "0.00",
                "unforeseen_expenses_award": "0.00",
                "civil_blame_award": "0.00",
                "docking_award": "0.00",
                "failure_award": "0.00",
                "flight_delay_award": "0.00",
                "certificate": 147
            },
            {
                "id": 116,
                "total_price": 58531.319045,
                "is_active": true,
                "is_available": true,
                "created_at": "1673601761",
                "modified_at": "1673601761",
                "last_name": null,
                "first_name": null,
                "middle_name": "pedrovich",
                "last_name_en": "petrov",
                "first_name_en": "per",
                "birth_date": "1960-01-01",
                "passport_series": null,
                "passport_number": null,
                "medical_award": "0.00",
                "insurance_award": "0.00",
                "sports_equipment_award": "0.00",
                "accident_award": "0.00",
                "baggage_award": "0.00",
                "cancellations_award": "0.00",
                "cancellations_d_award": "0.00",
                "unforeseen_expenses_award": "0.00",
                "civil_blame_award": "0.00",
                "docking_award": "0.00",
                "failure_award": "0.00",
                "flight_delay_award": "0.00",
                "certificate": 147
            }
        ],
        "user": {
            "id": 391,
            "login": "ra1n",
            "is_active": true,
            "created_at": "1672131239",
            "first_name": "Станислав",
            "last_name": "Порхачевский",
            "middle_name": null,
            "group": "Руководитель BestDoctor",
            "client_id": 12,
            "department": null
        },
        "is_comment": true,
        "certificate_name": "",
        "product_name": "test",
        "is_ready": true,
        "is_active": true,
        "is_available": false,
        "created_at": "1673601761",
        "modified_at": "1673601761",
        "traveling_type": "Однократная",
        "currency_type": "€",
        "insuring_type": "Физлицо",
        "traveling_abroad_rule": "1111",
        "traveling_abroad_type": "2222",
        "traveling_abroad_code": "3333",
        "clients_comment": "",
        "period": 0,
        "days_count": 0,
        "insurance_id": 1,
        "medicine_franchise": 0,
        "usd_rate": "63.49170",
        "eur_rate": "62.59030",
        "medical_award": "4.50",
        "insurance_award": "1868.05",
        "is_separated_policy": false,
        "start_alien": false,
        "is_template": true,
        "status": false,
        "date_from": "2022-10-14",
        "date_to": "2022-10-18",
        "accept_date": "2022-10-13",
        "amount_one_time_tariff": 511,
        "amount_multiple_tariff": null,
        "multiple_tariff": null,
        "one_time_tariff": 47,
        "traveling_abroad": 8
    }
}
