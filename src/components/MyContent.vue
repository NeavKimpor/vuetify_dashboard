<template>
<div class="bg">
    <div class="container">
        <!-- <div class="machine"> -->
        <div class="top-row">
            <div class="machine washer">
                <div class="bar">
                    <h5>Washer</h5>
                    <label class="switch">
                        <input type="checkbox" />
                        <span class="slider round"></span>
                    </label>
                </div>
                <div class="status">
                    <div class="graph1">
                        <svg>
                            <circle cx="90" cy="70" r="60" />
                        </svg>
                    </div>
                    <div class="info">
                        <p>ID : 1</p>
                        <p>Availability : 3/4</p>
                        <p>Countdown : 0 : 00 : 00</p>
                        <button class="button1">Available</button>
                    </div>
                </div>
            </div>
            <div class="machine washer">
                <div class="bar">
                    <h5>Washer</h5>
                    <label class="switch">
                        <input type="checkbox" />
                        <span class="slider round"></span>
                    </label>
                </div>
                <div class="status">
                    <div class="graph2">
                        <svg>
                            <circle cx="90" cy="70" r="60" />
                        </svg>
                    </div>
                    <div class="info">
                        <p>ID : 2</p>
                        <p>Availability : 2/4</p>
                        <p>Countdown : 0 : 00 : 00</p>
                        <button class="button2">Available</button>
                    </div>
                </div>
            </div>
            <div class="machine washer">
                <div class="bar">
                    <h5>Washer</h5>
                    <label class="switch">
                        <input type="checkbox" />
                        <span class="slider round"></span>
                    </label>
                </div>
                <div class="status">
                    <div class="graph3">
                        <svg>
                            <circle cx="90" cy="70" r="60" />
                        </svg>
                    </div>
                    <div class="info">
                        <p>ID : 3</p>
                        <p>Availability : 4/4</p>
                        <p>Countdown : 0 : 00 : 00</p>
                        <button class="button3">Out of use</button>
                    </div>
                </div>
            </div>
        </div>
        <div class="bot-row">
            <div class="machine dryer">
                <div class="bar">
                    <h5>Dryer</h5>
                    <label class="switch">
                        <input type="checkbox" />
                        <span class="slider round"></span>
                    </label>
                </div>
                <div class="status">
                    <div class="graph4">
                        <svg>
                            <circle cx="90" cy="70" r="60" />
                        </svg>
                    </div>
                    <div class="info">
                        <p>ID : 4</p>
                        <p>Availability : 2/4</p>
                        <p>Countdown : 0 : 00 : 00</p>
                        <button class="button4">Available</button>
                    </div>
                </div>
            </div>
            <div class="machine dryer">
                <div class="bar">
                    <h5>Dryer</h5>
                    <label class="switch">
                        <input type="checkbox" />
                        <span class="slider round"></span>
                    </label>
                </div>
                <div class="status">
                    <div class="graph5">
                        <svg>
                            <circle cx="90" cy="70" r="60" />
                        </svg>
                    </div>
                    <div class="info">
                        <p>ID : 5</p>
                        <p>Availability : 1/4</p>
                        <p>Countdown : 1 : 00 : 25</p>
                        <button class="button5">Unavailable</button>
                    </div>
                </div>
            </div>
            <div class="machine dryer">
                <div class="bar">
                    <h5>Dryer</h5>
                    <label class="switch">
                        <input type="checkbox" />
                        <span class="slider round"></span>
                    </label>
                </div>
                <div class="status">
                    <div class="graph6">
                        <svg>
                            <circle cx="90" cy="70" r="60" />
                        </svg>
                    </div>
                    <div class="info">
                        <p>ID : 6</p>
                        <p>Availability : 3/4</p>
                        <p>Countdown : 0 : 00 : 00</p>
                        <button class="button6">Available</button>
                    </div>
                </div>
            </div>
        </div>
        <!-- </div> -->
    </div>
</div>
    
</template>

<script>
export default {
    name: 'MyContent'
}
</script>
<style>
@import url("https://fonts.googleapis.com/css2?family=Roboto:wght@700&display=swap");
.bg {
    border: 1px solid #f6f4f4;
    background: #f6f4f4;
}
.container {
    /* height: 90%; */
    border: 1px solid#F6F4F4;
    /* padding: 15px; */
    margin: 1rem;
}
/* .machine {
    width: 30%;
    height: 250px;
    background: white;
    border-radius: 20px;
    box-shadow: 5px 10px 18px #8888;
} */
.machine {
    width: 30%;
    /* height: 50vh; */
    height: 38vh;
    background: white;
    border-radius: 20px;
    box-shadow: 5px 10px 18px #8888;
}
.bar {
    margin: 10px;
    height: 50px;
    display: flex;
    justify-content: space-between;
}
.bar h5 {
    /* margin-top: auto; */
    margin-left: 12px;
    font-size: 22px;
    font-family: "Roboto", sans-serif;
}
.top-row {
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    margin-top: 12px;
}
.bot-row {
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    margin-top: 25px;
}
.status {
    display: flex;
    flex-direction: row;
    justify-content: space-evenly;
}
svg {
    width: 200px;
    height: 150px;
}
svg circle {
    fill: transparent;
    stroke-width: 20px;
}
.graph1 {
    stroke: #4bbade;
    stroke-dasharray: 460;
    stroke-dashoffset: 100%;
}
.button1 {
    background: #58e018;
}
.graph2 {
    stroke: #4bbade;
    stroke-dasharray: 365;
    stroke-dashoffset: 100%;
}
.button2 {
    background: #58e018;
}
.graph3 {
    stroke: #e95656;
    stroke-dasharray: 0;
    stroke-dashoffset: 100%;
}
.button3 {
    background: #f13939;
}
.graph4 {
    stroke: #4bbade;
    stroke-dasharray: 365;
    stroke-dashoffset: 100%;
}
.button4 {
    background: #58e018;
}
.graph5 {
    stroke: #e95656;
    stroke-dasharray: 274;
    stroke-dashoffset: 100%;
}
.button5 {
    background: #f13939;
}
.graph6 {
    stroke: #4bbade;
    stroke-dasharray: 460;
    stroke-dashoffset: 100%;
}
.button6 {
    background: #58e018;
}
.info {
    /* margin-top: 10px; */
    font-size: 15px;
    /* line-height: 2.5; */
    font-family: "Roboto", sans-serif;
    font-weight: bold;
}
.info p {
    line-height: 1.5;
}
.info button {
    /* margin-top: 20px; */
    margin-top: 25px;
    padding: 8px;
    width: 87px;
    height: 38px;
    border-radius: 13px;
    color: white;
    border: 0;
    font-weight: bold;
}

.switch {
    position: relative;
    display: inline-block;
    width: 60px;
    height: 34px;
}

.switch input {
    opacity: 0;
    width: 0;
    height: 0;
}

.slider {
    position: absolute;
    cursor: pointer;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    background-color: #58e018;
    -webkit-transition: 0.4s;
    transition: 0.4s;
}

.slider:before {
    position: absolute;
    content: "";
    height: 26px;
    width: 26px;
    left: 4px;
    bottom: 4px;
    background-color: white;
    -webkit-transition: 0.4s;
    transition: 0.4s;
}

input:checked + .slider {
    background-color: #f13939;
}

input:focus + .slider {
    box-shadow: 0 0 1px #f13939;
}

input:checked + .slider:before {
    -webkit-transform: translateX(26px);
    -ms-transform: translateX(26px);
    transform: translateX(26px);
}

/* Rounded sliders */
.slider.round {
    border-radius: 34px;
}

.slider.round:before {
    border-radius: 50%;
}

@media screen and (max-width: 1200px) {
    .top-row {
        display: flex;
        flex-direction: column;
        margin-top: 7px;
        width: 95vw;
        align-items: center;
        /* width: 120%; */
        /* width: 100vw; */
        /* gap: 4; */
    }
    .bot-row {
        display: flex;
        flex-direction: column;
        justify-content: space-between;
        margin-top: 7px;
        align-items: center;
        width: 95vw;
    }
    .machine {
        margin-top: 2vh;
        width: 95%;
        /* height: 50vh; */
        height: auto;
        background: white;
        border-radius: 20px;
        box-shadow: 5px 10px 18px #8888;
    }
    .top-row .machine {
        margin-bottom: 4rem;
    }
    .bot-row .machine {
        margin-bottom: 4rem;
    }
    svg {
        height: 150px;
        width: 200px;
        padding: 1rem;
    }
    .info {
        width: auto;
        height: auto;
    }
}
</style>