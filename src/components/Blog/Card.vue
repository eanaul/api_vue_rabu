<template>
    <div>
        <div class="card-blog">
            <img src="@/assets/img/portfolio-1.jpg" alt="">
            <div class="card-blog-description">
                <div class="time">
                    Dec 3rd 2023
                </div>
                <h4>Lorem ipsum dolor sit amet.</h4>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quisquam, quod.</p>
            </div>
        </div>
    </div>
</template>

<style>
.card-blog {
    text-align: start;
    box-shadow: 0px 10px 30px rgba(0, 0, 0, 0.05);
    background: white;
    transition: all 0.5s ease;
    margin: 10px 10px;
    display: flex;
    align-items: center;
}

.card-blog img {
    width: 200px;
    height: 200px;
    object-fit: contain;
    padding: 0 0 20px 20px;
}

.card-blog-description {
    margin-top: 50px;
    padding: 0 20px 20px 20px;
}

.card-blog h4 {
    margin-top: 10px;
    font-weight: 900;
    font-size: 30px;
    line-height: 35px;
    margin-bottom: 0;
    color: #042181;
}

@media screen and (max-width: 600px) {
    
    .row-blog{
        display: grid;
        grid-template-columns: repeat(1, 1fr);
        grid-gap: 10px
    }

    .card-blog{
        flex-direction: column;
        align-items: start;
    }

    .card-blog img {
        width: 100%;
        height: 260px;
        object-fit: contain;
}
}
</style>