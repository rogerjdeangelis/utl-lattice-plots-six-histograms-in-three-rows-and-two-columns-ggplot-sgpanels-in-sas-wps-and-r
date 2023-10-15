# utl-lattice-plots-six-histograms-in-three-rows-and-two-columns-ggplot-sgpanels-in-sas-wps-and-r
Lattice plots six histograms in three rows and two columns spanels in sas wps and r
    %let pgm=utl-lattice-plots-six-histograms-in-three-rows-and-two-columns-ggplot-sgpanels-in-sas-wps-and-r;

    Lattice plots six histograms in three rows and two columns spanels in sas wps and r
    
    https://tinyurl.com/bdevm7f8
    https://github.com/rogerjdeangelis/utl-lattice-plots-six-histograms-in-three-rows-and-two-columns-ggplot-sgpanels-in-sas-wps-and-r/blob/main/spider_r.png

    https://tinyurl.com/35krptww
    https://github.com/rogerjdeangelis/utl-lattice-plots-six-histograms-in-three-rows-and-two-columns-ggplot-sgpanels-in-sas-wps-and-r/blob/main/spider_wps.png

    https://tinyurl.com/yz9rmetc
    https://github.com/rogerjdeangelis/utl-lattice-plots-six-histograms-in-three-rows-and-two-columns-ggplot-sgpanels-in-sas-wps-and-r/blob/main/spider_sas.png

     Solutions

         1 wps r
         2 wps base
         3 sas

    SOAPBOX ON

    NOTE: GGPLOT IS SUPPORTED IN PYTHON, BUT NOT AS MATURE AS IN R?
    https://realpython.com/ggplot-python/

    WPS/Altair does not support all the bells and whistles of SAS ods graphics but does appear
    to provide both sg and legacy graphics, however, easy integration with R and support
    for legacy graphics more than compensates for the loss of bells and whistles in ods sggraphics.

    SOAPBOX ON

    github
    https://tinyurl.com/yswz7zet
    https://github.com/rogerjdeangelis/utl-lattice-plots-six-histograms-in-three-rows-and-two-columns-ggplot-sgpanels-in-sas-wps-and-r

    stackoverflow R
    https://tinyurl.com/k49wjwbw
    https://stackoverflow.com/questions/77280081/how-to-stack-graphs-on-top-of-each-other-with-two-segments-each-in-ggplot


    /*           _               _
      ___  _   _| |_ _ __  _   _| |_
     / _ \| | | | __| `_ \| | | | __|
    | (_) | |_| | |_| |_) | |_| | |_
     \___/ \__,_|\__| .__/ \__,_|\__|
                    |_|
    */

     /**************************************************************************************************************************/
     /*                                                                                                                        */
     /*                                                 Spider life stages                                                     */
     /*                                                                                                                        */
     /*                   Nedr                                                   Rinn                               Lifestage  */
     /*                                                                                                                        */
     /*       2022-03 2022-05 2022-06 2022-07 2022-08 2022-09     2022-03 2022-04 2022-05 2022-06 2022-07 2022-08              */
     /*    -------------------------------------------------------------------------------------------------------             */
     /* 30 +                                                   +                                                  + 30         */
     /*    |                                                   |                                                  |            */
     /* 25 +                   XXXXX                           +   XXXXX                                          + 25         */
     /*    |   XXXXX           XXXXX                           |   XXXXX                                          |            */
     /* 20 +   XXXXX           XXXXX                           +   XXXXX                                          + 20   LARGE */
     /*    |   XXXXX           XXXXX                           |   XXXXX                                          |            */
     /* 15 +   XXXXX   XXXXX   XXXXX                           +   XXXXX           XXXXX                          + 15         */
     /*    |   XXXXX   XXXXX   XXXXX                           |   XXXXX   XXXXX   XXXXX                          |            */
     /* 10 +   XXXXX   XXXXX   XXXXX                           +   XXXXX   XXXXX   XXXXX                          + 10         */
     /*    |   XXXXX   XXXXX   XXXXX                           |   XXXXX   XXXXX   XXXXX                   XXXXX  |            */
     /*  5 +   XXXXX   XXXXX   XXXXX           XXXXX   XXXXX   +   XXXXX   XXXXX   XXXXX   XXXXX           XXXXX  +  5         */
     /*    |   XXXXX   XXXXX   XXXXX   XXXXX   XXXXX   XXXXX   |   XXXXX   XXXXX   XXXXX   XXXXX   XXXXX   XXXXX  |            */
     /*    --------------------------------------------------------------------------------------------------------            */
     /* 30 +                                                   +           XXXXX                           XXXXX  + 30         */
     /*    |                                                   |           XXXXX                           XXXXX  |            */
     /* 25 +                                                   +           XXXXX           XXXXX           XXXXX  + 25         */
     /*    |                                                   |           XXXXX   XXXXX   XXXXX           XXXXX  |            */
     /* 20 +                                           XXXXX   +           XXXXX   XXXXX   XXXXX           XXXXX  + 20   MIDLE */
     /*    |                           XXXXX   XXXXX   XXXXX   |           XXXXX   XXXXX   XXXXX   XXXXX   XXXXX  |            */
     /* 15 +   XXXXX           XXXXX   XXXXX   XXXXX   XXXXX   +   XXXXX   XXXXX   XXXXX   XXXXX   XXXXX   XXXXX  + 15         */
     /*    |   XXXXX           XXXXX   XXXXX   XXXXX   XXXXX   |   XXXXX   XXXXX   XXXXX   XXXXX   XXXXX   XXXXX  |            */
     /* 10 +   XXXXX           XXXXX   XXXXX   XXXXX   XXXXX   +   XXXXX   XXXXX   XXXXX   XXXXX   XXXXX   XXXXX  + 10         */
     /*    |   XXXXX           XXXXX   XXXXX   XXXXX   XXXXX   |   XXXXX   XXXXX   XXXXX   XXXXX   XXXXX   XXXXX  |            */
     /*  5 +   XXXXX   XXXXX   XXXXX   XXXXX   XXXXX   XXXXX   +   XXXXX   XXXXX   XXXXX   XXXXX   XXXXX   XXXXX  +  5         */
     /*    |   XXXXX   XXXXX   XXXXX   XXXXX   XXXXX   XXXXX   |   XXXXX   XXXXX   XXXXX   XXXXX   XXXXX   XXXXX  |            */
     /*    ---------------------------------------------------------------------------------------------------------           */
     /* 30 +   XXXXX                                           +                           XXXXX                  + 30         */
     /*    |   XXXXX                                           |           XXXXX           XXXXX                  |            */
     /* 25 +   XXXXX                   XXXXX                   +           XXXXX           XXXXX                  + 25         */
     /*    |   XXXXX                   XXXXX                   |           XXXXX           XXXXX                  |      SMALL */
     /* 20 +   XXXXX                   XXXXX   XXXXX   XXXXX   +           XXXXX           XXXXX                  + 20         */
     /*    |   XXXXX   XXXXX           XXXXX   XXXXX   XXXXX   |           XXXXX           XXXXX                  |            */
     /* 15 +   XXXXX   XXXXX           XXXXX   XXXXX   XXXXX   +   XXXXX   XXXXX           XXXXX           XXXXX  + 15         */
     /*    |   XXXXX   XXXXX           XXXXX   XXXXX   XXXXX   |   XXXXX   XXXXX           XXXXX           XXXXX  |            */
     /* 10 +   XXXXX   XXXXX   XXXXX   XXXXX   XXXXX   XXXXX   +   XXXXX   XXXXX   XXXXX   XXXXX           XXXXX  + 10         */
     /*    |   XXXXX   XXXXX   XXXXX   XXXXX   XXXXX   XXXXX   |   XXXXX   XXXXX   XXXXX   XXXXX           XXXXX  |            */
     /*  5 +   XXXXX   XXXXX   XXXXX   XXXXX   XXXXX   XXXXX   +   XXXXX   XXXXX   XXXXX   XXXXX           XXXXX  +  5         */
     /*    |   XXXXX   XXXXX   XXXXX   XXXXX   XXXXX   XXXXX   |   XXXXX   XXXXX   XXXXX   XXXXX   XXXXX   XXXXX  |            */
     /*    --------------------------------------------------------------------------------------------------------            */
     /*       2022-03 2022-05 2022-06 2022-07 2022-08 2022-09     2022-03 2022-04 2022-05 2022-06 2022-07 2022-08              */
     /*                                                                                                                        */
     /*                                                       Date                                                             */
     /*                                                                                                                        */
     /**************************************************************************************************************************/

    /*                   _
    (_)_ __  _ __  _   _| |_
    | | `_ \| `_ \| | | | __|
    | | | | | |_) | |_| | |_
    |_|_| |_| .__/ \__,_|\__|
            |_|
    */
    options validvarname=upcase ps=65 ls=255;
    libname sd1 "d:/sd1";
    data sd1.have ;
       format dato yymmdd10.;
       informat place $4. LLIFESTAGES $5. dato yymmdd10. ;
       input  DATO    PLACE    LLIFESTAGES     COUNT;
       *count = count+1;;
    cards4;
    2022-03-01 Nedr LARGE 22
    2022-04-01 Nedr LARGE 16
    2022-05-01 Nedr LARGE 26
    2022-06-01 Nedr LARGE 2
    2022-07-01 Nedr LARGE 5
    2022-08-01 Nedr LARGE 4
    2021-03-01 Nedr MIDLE 14
    2022-04-01 Nedr MIDLE 5
    2022-05-01 Nedr MIDLE 15
    2022-06-01 Nedr MIDLE 18
    2022-07-01 Nedr MIDLE 17
    2022-08-01 Nedr MIDLE 20
    2022-09-01 Nedr SMALL 20
    2022-03-01 Nedr SMALL 29
    2022-05-01 Nedr SMALL 17
    2022-06-01 Nedr SMALL 11
    2022-07-01 Nedr SMALL 25
    2022-08-01 Nedr SMALL 21
    2022-03-01 Rinn LARGE 24
    2022-04-01 Rinn LARGE 12
    2022-05-01 Rinn LARGE 16
    2022-06-01 Rinn LARGE 4
    2022-07-01 Rinn LARGE 2
    2022-08-01 Rinn LARGE 7
    2022-03-01 Rinn MIDLE 15
    2022-04-01 Rinn MIDLE 30
    2022-05-01 Rinn MIDLE 23
    2022-06-01 Rinn MIDLE 26
    2022-07-01 Rinn MIDLE 18
    2022-08-01 Rinn MIDLE 29
    2022-03-01 Rinn SMALL 14
    2022-04-01 Rinn SMALL 27
    2022-05-01 Rinn SMALL 11
    2022-06-01 Rinn SMALL 30
    2022-07-01 Rinn SMALL 2
    2022-08-01 Rinn SMALL 16
    ;;;;
    run;quit;

    /**************************************************************************************************************************/
    /*                                                  |                                                                      */
    /*  INPUT                                           |   PROCESS                                                            */
    /*                                                  |                                                                      */
    /*  SD1.HAVE with formatted variables  total obs=36 |                                                                      */
    /*      DATO       PLACE    LLIFESTAGES    COUNT    |                                                                      */
    /*                                                  |                                                                      */
    /*   2022-03-01    Nedr        LARGE         22     |   options ps=24 ls=64;                                               */
    /*   2022-04-01    Nedr        LARGE         16     |   title "Spider life stages";                                        */
    /*   2022-05-01    Nedr        LARGE         26     |   proc chart data=sd1.have;                                          */
    /*   2022-06-01    Nedr        LARGE          2     |   format dato yymmd7.;                                               */
    /*   2022-07-01    Nedr        LARGE          5     |   label count= "Amount small spiders";                               */
    /*   2022-08-01    Nedr        LARGE          4     |   label dato = "Date";                                               */
    /*   2022-09-01    Nedr        MIDLE         14     |   by place llifestages;                                              */
    /*   2022-04-01    Nedr        MIDLE          5     |   vbar dato / discrete sumvar=count space=3 axis=0 to 30 by 5;       */
    /*   2022-05-01    Nedr        MIDLE         15     |   run;quit;                                                          */
    /*   2022-06-01    Nedr        MIDLE         18     |                                                                      */
    /*   2022-07-01    Nedr        MIDLE         17     | You have to do a little editios, much easier the editing sq graphics */
    /*   2022-08-01    Nedr        MIDLE         20     |                                                                      */
    /*   2022-09-01    Nedr        SMALL         20     |                                                                      */
    /*   2022-04-01    Nedr        SMALL         29     |                                                                      */
    /*   2022-05-01    Nedr        SMALL         17     |                                                                      */
    /*   2022-06-01    Nedr        SMALL         11     |                                                                      */
    /*   2022-07-01    Nedr        SMALL         25     |                                                                      */
    /*   2022-08-01    Nedr        SMALL         21     |                                                                      */
    /*   2021-09-01    Rinn        LARGE         24     |                                                                      */
    /*   2022-04-01    Rinn        LARGE         12     |                                                                      */
    /*   2022-05-01    Rinn        LARGE         16     |                                                                      */
    /*   2022-06-01    Rinn        LARGE          4     |                                                                      */
    /*   2022-07-01    Rinn        LARGE          2     |                                                                      */
    /*   2022-08-01    Rinn        LARGE          7     |                                                                      */
    /*   2021-09-01    Rinn        MIDLE         15     |                                                                      */
    /*   2022-04-01    Rinn        MIDLE         30     |                                                                      */
    /*   2022-05-01    Rinn        MIDLE         23     |                                                                      */
    /*   2022-06-01    Rinn        MIDLE         26     |                                                                      */
    /*   2022-07-01    Rinn        MIDLE         18     |                                                                      */
    /*   2022-08-01    Rinn        MIDLE         29     |                                                                      */
    /*   2021-09-01    Rinn        SMALL         14     |                                                                      */
    /*   2022-04-01    Rinn        SMALL         27     |                                                                      */
    /*   2022-05-01    Rinn        SMALL         11     |                                                                      */
    /*   2022-06-01    Rinn        SMALL         30     |                                                                      */
    /*   2022-07-01    Rinn        SMALL          2     |                                                                      */
    /*   2022-08-01    Rinn        SMALL         16     |                                                                      */
    /*                                                  |                                                                      */
    /***************************************************************************************************************************/

    /*
    / | __      ___ __  ___   _ __
    | | \ \ /\ / / `_ \/ __| | `__|
    | |  \ V  V /| |_) \__ \ | |
    |_|   \_/\_/ | .__/|___/ |_|
                 |_|
    */
    %utlfkil(d:/png/spider_r.png);

    %utl_submit_wps64x('
    libname sd1 "d:/sd1";
    proc r;           ;
    export data=sd1.havfin r=have;
    submit;
    library(dplyr);
    library(tidyr);
    library(scales);
    library(ggplot2);
    combined <- ggplot(have, aes(x = DATO, y = COUNT))+
      labs(title = "Spider life stages",
           x = "Date", y = "Amount small spiders")+
      guides(x =  guide_axis(angle = 90)) +
      facet_grid(LLIFESTAGES ~ PLACE)+
      scale_x_date(breaks=date_breaks("1 month"), labels=date_format("%Y-%m-%d"))+
      theme_bw()+
      geom_bar(stat = "identity", position = "dodge", width = 15, fill="lightgray");
    png("d:/png/spider_r.png",width = 800, height = 600);
    combined;
    png();
    endsubmit;
    run;quit;
    ');


    /*
    | | ___   __ _
    | |/ _ \ / _` |
    | | (_) | (_| |
    |_|\___/ \__, |
             |___/
    */

    /**************************************************************************************************************************/
    /*                                                                                                                        */
    /*  > library(tidyr)                                                                                                      */
    /*  > library(scales)                                                                                                     */
    /*  > library(ggplot2)                                                                                                    */
    /*  > combined <- ggplot(have, aes(x = DATO, y = COUNT))+  labs(titl                                                      */
    /*  e = "Spider life stages",       x = "Date", y = "Amount small sp                                                      */
    /*  iders")+  guides(x =  guide_axis(angle =                                                                              */
    /*  90)) +  facet_grid(LLIFESTAGES ~ PLACE)+  scale_x_date(breaks=da                                                      */
    /*  te_breaks("1 month"),                                                                                                 */
    /*  +  labels=date_format("%Y-%m-%d"))+  theme_bw()+  geom_bar(stat                                                       */
    /*  = "identity", position = "dodge", width = 15, fill="lightgray")                                                       */
    /*  > png("d:/png/spider_r.png",width = 800, height = 600)                                                                */
    /*  > combined                                                                                                            */
    /*  > png()                                                                                                               */
    /**************************************************************************************************************************/
    /*___                         _
    |___ \  __      ___ __  ___  | |__   __ _ ___  ___
      __) | \ \ /\ / / `_ \/ __| | `_ \ / _` / __|/ _ \
     / __/   \ V  V /| |_) \__ \ | |_) | (_| \__ \  __/
    |_____|   \_/\_/ | .__/|___/ |_.__/ \__,_|___/\___|
                     |_|
    */

    %utlfkil(d:/png/spider_wps.png);
    %utl_submit_wps64x('
    libname sd1 "d:/sd1";
    filename outfile "d:/png/spider_wps.png";
    goptions
          reset=global
          gsfmode = replace
          device  = png
          gsfname = outfile
          vsize=8in
          hsize=10in
          htext=12pt ;
    run;quit;
    title "Spider life stages";
    proc sgpanel data=sd1.havfin;
    label dato  = "Date";
    label count = "Spiders";
    panelby place llifestages / layout=lattice onepanel novarname sparse;
    vbar dato / response=count barwidth=0.3;
    rowaxis label="Months" interval=month ;
    run;quit;
    filename outfile clear;
    ');

    /*
    | | ___   __ _
    | |/ _ \ / _` |
    | | (_) | (_| |
    |_|\___/ \__, |
             |___/
    */

    /**************************************************************************************************************************/
    /*                                                                                                                        */
    /* NOTE: Library sd1 assigned as follows:                                                                                 */
    /*       Engine:        SAS7BDAT                                                                                          */
    /*       Physical Name: d:\sd1                                                                                            */
    /*                                                                                                                        */
    /* 2         filename outfile "d:/png/spider_wps.png";                                                                    */
    /* 3         goptions      reset=global      gsfmode = replace                                                            */
    /*  device  = png      gsfname = outfile      vsize=8in      hsize=                                                       */
    /* 10in      htext=12pt;                                                                                                  */
    /* 4         run;                                                                                                         */
    /* 5         quit;                                                                                                        */
    /* 6         title "Spider life stages";                                                                                  */
    /* 7         proc sgpanel data=sd1.havfin;                                                                                */
    /* 8         *format dato mmyyD7.;                                                                                        */
    /* 9         *format dato yymmdd10.;                                                                                      */
    /* 10        label dato  = "Date";                                                                                        */
    /* 11        label count = "Spiders";                                                                                     */
    /* 12        panelby place llifestages / layout=lattice onepanel no                                                       */
    /* varname sparse;                                                                                                        */
    /* 13        vbar dato / response=count barwidth=0.3;                                                                     */
    /* 14        rowaxis label="Months" interval=month;                                                                       */
    /* 15        run;                                                                                                         */
    /* NOTE: Successfully written image d:\png\spider_wps.png                                                                 */
    /*                                                                                                                        */
    /**************************************************************************************************************************/

    /*____
    |___ /   ___  __ _ ___
      |_ \  / __|/ _` / __|
     ___) | \__ \ (_| \__ \
    |____/  |___/\__,_|___/

    */

    libname sd1 "d:/sd1";
    ods listing gpath="d:\png" style=analysis;
    ods graphics on / reset=index width=7in height=7in imagefmt=png imagename='spided_sas';
    title "Spider life stages";
    proc sgpanel data=sd1.havfin;
    *format dato mmyyD7.;
    *format dato yymmdd10.;
    label dato  = "Date";
    label count = "Spiders";
    panelby place llifestages / layout=lattice onepanel novarname sparse;
    vbar dato / response=count barwidth=0.3;
    rowaxis label="Months" interval=month ;
    run;quit;

    /*              _
      ___ _ __   __| |
     / _ \ `_ \ / _` |
    |  __/ | | | (_| |
     \___|_| |_|\__,_|

    */
