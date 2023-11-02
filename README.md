* {
    margin: 0%;
    padding: 0%;
    box-sizing: border-box;
}

/*   */

@media only screen and (min-width: 992px) {
    .setting-frame {
        display: flex;
        justify-content: center;
    }


    .offcanvas-body .navbar-nav {
        padding-right: 200px !important;
    }


    .nav-item a {
        color: var(--Gray-222, #222);
        /* Menu Text */
        font-family: Lato;
        font-size: 14px;
        font-style: normal;
        font-weight: 700;
        line-height: 20px;
        /* 142.857% */
        text-transform: uppercase;
    }


    .introduce {
        background-image: url(./img/showcase-bg.svg);
        background-repeat: no-repeat;
        background-size: contain;
        width: 100%;
        height: 888px;
    }


    .introduce .introduce__content p,
    .introduce .introduce__content h1 {
        color: #FFF;

        /* Tag (16px) */
        font-family: Lato;
        font-style: normal;
        font-weight: 700;
        line-height: 24px;
        /* 150% */
        text-transform: uppercase;
    }

    .introduce__content p {
        font-size: 16px;
    }

    .introduce__content h1 {
        font-size: 60px;
    }



    .product__man {
        background-image: url(./img/Showcase-product\ \(1\).svg);
        background-repeat: no-repeat;
        background-size: cover;
        height: 279px;
    }

    .product__woman {
        background-image: url(./img/Showcase-product\ \(1\)2.svg);
        background-repeat: no-repeat;
        background-size: cover;
        height: 279px;
    }

    .product__kid {
        background-image: url(./img/Showcase-product\ \(1\)3.svg);
        background-repeat: no-repeat;
        background-size: cover;
        height: 279px;
    }


    .introduce__content {
        padding-top: 50px;
    }

    .text-intro2 {
        padding-top: 20px;
    }

    .showproduct__pants {
        background-image: url(./img/pants.svg);
        background-repeat: no-repeat;
        background-size: cover;
        height: 260.406px;
    }

    .showproduct__jeans {
        background-image: url(./img/jeans.svg);
        background-repeat: no-repeat;
        background-size: cover;
        height: 260.406px;
    }

    .showproduct__Tshirt {
        background-image: url(./img/tshirts.svg);
        background-repeat: no-repeat;
        background-size: cover;
        height: 260.406px;
    }

    .showproduct__Jacket {
        background-image: url(./img/jacket.svg);
        background-repeat: no-repeat;
        background-size: cover;
        height: 545.123px;
    }

}