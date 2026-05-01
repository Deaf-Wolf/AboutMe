# Replication Data
The Copany name is BambuLab
The Images are in ~/src/img

Mobile layout first

## MainLayout
The MainLayout is basic:
Header, Content, Footer

[   Header  ]
|           |
|           |
|           |
[   Footer  ]

## The Header
The Header will show on the right side the Hamburgermenu and the Copany Logo(/src/img/logo.png).
On the Left side display a Search icon, Warenkorbwagen, Profile icon (/home/wolf/Projects/AboutMe/src/img/profile omg.png)


It uses the folowing css for background:
.bg-white {
    --tw-bg-opacity: 1;
    background-color: rgb(255 255 255 / var(--tw-bg-opacity, 1));
}


## The Content

The Content has a light grey background:
.bg-bbl-grey-2
{
    background-color: var(--bbl-grey-2); // #f5f5f5
}

The Top Center will display a h1 title "Bestellstatus"

Then the Order Details are build in cards. 
The Cards have a withe background a a light shadow to make it look floating.

The First Card Will displat the Bestellnr as copy able text, with the copy icon at the end. "Bestell-Nr:EN726734690659975169"
The Text and Icon will have color:
.text-brand-color {
    --tw-text-opacity: 1;
    color: rgb(0 174 66 / var(--tw-text-opacity, 1));
}  

then it will the show the order date in normal text color. "Bestellung aufgegeben: 27.April.2000"

then a order status in a Pillshaped container with the status : (Unterwegs)
the badge will have a transparent yellow background and darker yellow non transparent text color.

Layout:
__________________________
| Bestell-NR.:xyz        | <- bold and green
| Bestellung aufgegeben  |
| (Unterwegs)            | <- Status Pill
|________________________|

a lil margin then next card with the Order Info:

Card title on left: "Zahlungsdetails"
Then the order info 
The imgae is /src/img/printer.png
_____________________________________
| _______(1)                         |
| |       | Bambu Lab A1 3D Printer  | <- Bold
| |  img  | A1 Combo                 | <- sub title in light fray
| |_______| Free                     | <- Bold
|____________________________________|
|   Zwischensumme           0,00 E   |
|   Versand            1 mal Beten   | <- This section will have grey text
|   Steuer             1 Bier        |
|   ______________________________   |
|   Gesamtsumme             26 Jahre | <- bold but grey
|                                    |
|<h3> Bruttobetrag        Geburstag  |
|____________________________________|

Then the Lieferadress

________________________________
| Lieferadresse    <bold>       |
|   - Daniel Schmitd            |  <- points in light grey
|   - Belgium                   |
|   - Alles gute zum Geburstag  |
|_______________________________|




## Footer 
is empty with the same bg as header