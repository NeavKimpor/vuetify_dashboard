<template>
    <div class="container">
        <!-- <div class="machine"> -->
            <div class="top-row">
                <div class="machine washer">
                    <div class="bar">
                        <h5>Washer</h5>
                        <label class="switch">
                            <input type="checkbox">
                            <div class="switch-btn"></div>
                        </label>
                    </div>
                    <div class="status">
                        <div class="graph">
                            <!-- <svg>
                                <circle cx="125" cy="70" r="60"></circle>
                            </svg> -->
                        </div>
                        <div class="info">
                            <p>ID : 1</p>
                            <p>Availability : 1/4</p>
                            <p>Countdown : 0 : 00 : 00</p>
                            <button>Available</button>
                        </div>
                    </div>

                </div>
                <div class="machine washer">
                    <div class="bar">
                        <h5>Washer</h5>
                        <p>toggle</p>
                    </div>
                    <div class="status">
                        <div class="graph">
                            <!-- <svg>
                                <circle cx="125" cy="70" r="60"></circle>
                            </svg> -->
                        </div>
                        <div class="info">
                            <p>ID : 2</p>
                            <p>Availability : 1/4</p>
                            <p>Countdown : 0 : 00 : 00</p>
                            <button>Available</button>
                        </div>
                    </div>

                </div>
                <div class="machine washer">
                    <div class="bar">
                        <h5>Washer</h5>
                        <p>toggle</p>
                    </div>
                    <div class="status">
                        <div class="graph">
                            <!-- <svg>
                                <circle cx="125" cy="70" r="60"></circle>
                            </svg> -->
                        </div>
                        <div class="info">
                            <p>ID : 3</p>
                            <p>Availability : 1/4</p>
                            <p>Countdown : 0 : 00 : 00</p>
                            <button>Available</button>
                        </div>
                    </div>

                </div>
            </div>

            <div class="bot-row">
                <div class="machine dryer">
                    <div class="bar">
                        <h5>Dryer</h5>
                        <p>toggle</p>
                    </div>
                    <div class="status">
                        <div class="graph">
                            <!-- <svg>
                                <circle cx="125" cy="70" r="60"></circle>
                            </svg> -->
                        </div>
                        <div class="info">
                            <p>ID : 4</p>
                            <p>Availability : 1/4</p>
                            <p>Countdown : 0 : 00 : 00</p>
                            <button>Available</button>
                        </div>
                    </div>
                </div>
                <div class="machine dryer">
                    <div class="bar">
                        <h5>Dryer</h5>
                        <p>toggle</p>
                    </div>
                    <div class="status">
                        <div class="graph">
                            <!-- <svg>
                                <circle cx="125" cy="70" r="60"></circle>
                            </svg> -->
                        </div>
                        <div class="info">
                            <p>ID : 5</p>
                            <p>Availability : 1/4</p>
                            <p>Countdown : 0 : 00 : 00</p>
                            <button>Available</button>
                        </div>
                    </div>
                </div>
                <div class="machine dryer">
                    <div class="bar">
                        <h5>Dryer</h5>
                        <p>toggle</p>
                    </div>
                    <div class="status">
                        <div class="graph">
                            <!-- <svg>
                                <circle cx="125" cy="70" r="60"></circle>
                            </svg> -->
                        </div>
                        <div class="info">
                            <p>ID : 6</p>
                            <p>Availability : 1/4</p>
                            <p>Countdown : 0 : 00 : 00</p>
                            <button>Available</button>
                        </div>
                    </div>
                </div>
            </div>
        <!-- </div> -->
    </div>
</template>

<script>
export default {
    name : 'MyContent'
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@700&display=swap');
.container{
    background: #F6F4F4;
    height: 90%;
    border: 1px solid#F6F4F4;
    padding: 10px
;
}
.machine {
    width: 30%;
    height: 250px;
    background: white;
    border-radius: 20px;
    box-shadow: 5px 10px 18px #8888;
    /* border: 2px solid black; */
}
.bar {
    margin: 10px;
    height: 50px;
    display: flex;
    justify-content: space-between;
}
.bar h5 {
    margin-left: 12px;
    font-size: 22px;
    font-family: 'Roboto', sans-serif;
}
.bar p {
    font-size: 10px;
}
.top-row{
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    margin-top: 17px;
}
.bot-row{
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    margin-top: 25px;
}
.status{
    display: flex;
    flex-direction: row;
    justify-content: space-evenly;
}
/* .graph svg circle{
    fill: transparent;
    stroke: #4BBADE;
    stroke-width: 20px;
    stroke-dasharray: 500;
    stroke-dashoffset: 250;
} */
.info{
    font-size: 15px;
    /* line-height: 2.5; */
    font-family: 'Roboto', sans-serif;
    font-weight: bold;
}
.info p{
    line-height: 1.5;
}
.info button {
    margin-top: 20px;
    padding: 8px;
    width: 87px;
    height: 38px;
    border-radius: 13px;
    color: white;
    background: #58E018;
    border: 0;
    font-weight: bold;
}

.switch-btn{
    width: 80px;
    height: 40px;
    background: #e5e5e5;
    position: relative;
}
.switch-btn:before {
    content: '';
    position: absolute;
    height: 36px;
    width: 36px;
    background: #FFF;
    left: 2px;
    top: 2px;
}
input[type=checkbox]:checked + .switch-btn:before{
    left: 42px;
}
/* .toggle{
    width: 40px;
    height: calc(var(width)/2);
    border-radius: calc(var(height)/2);
    display: inline-block;
    cursor: pointer;
}
.toggle-input{
    display: none;
}
.toggle-fill {
    position: relative;
    width: var(width);
    height: var(height);
    border-radius: var(border-radius);
    background: #8888;
    transition: background 0.2s;
} */
</style>