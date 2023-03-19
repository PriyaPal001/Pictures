<div class="imageGrid">
    <img src="https://i.pinimg.com/564x/92/2a/76/922a76037e1a7b44f1213a802d93f532.jpg" alt="">
    <img src="https://i.pinimg.com/474x/cb/e6/11/cbe6116a6fbf27478640995ca7e5761b.jpg" alt="">
    <img src="https://i.pinimg.com/236x/f7/23/bc/f723bccbe621cc750389893b9bd787e3.jpg" alt="">
    <img src="https://i.pinimg.com/236x/73/d6/9f/73d69f46dcbf372b667e5b0289f657d5.jpg" alt="">
    <img src="https://i.pinimg.com/236x/1f/dc/79/1fdc79cf664071feae7de77e95b70ed8.jpg" alt="">
    <img src="https://i.pinimg.com/474x/4b/85/c1/4b85c13ba62ed2c69eb6c6bce026beb2.jpg" alt="">
    <img src="https://i.pinimg.com/236x/af/04/c6/af04c6cb9f6b393154f9637bb5016026.jpg" alt="">
    <img src="https://i.pinimg.com/736x/a9/6d/d5/a96dd5600fb33ac3922a70e1b5a0f0cf.jpg" alt="">
    <img src="https://i.pinimg.com/236x/e1/99/b2/e199b25cd826924f861cf8762eee449c.jpg" alt="">
    <img src="https://i.pinimg.com/236x/90/d9/73/90d973cd4637f52f8b0cbe2e71ef3f7c.jpg" alt="">
    <img src="https://i.pinimg.com/236x/e4/55/29/e45529711c1a705ef06df5228061f5c5.jpg" alt="">
    <img src="https://i.pinimg.com/736x/38/2c/84/382c848c9c4e32af8a48725669b5c1d0.jpg" alt="">
    <img src="https://i.pinimg.com/236x/45/49/da/4549da99a56dcd2d23a3223cb2531606.jpg" alt="">
    <img src="https://i.pinimg.com/236x/57/55/98/575598116b387a356908dc2c5f4b8f60.jpg" alt="">
    <img src="https://i.pinimg.com/236x/f6/16/d0/f616d09e383b9f108b6497a0f69e2578.jpg" alt="">
    <img src="https://i.pinimg.com/236x/d3/55/26/d35526348a2048e58775ab3803597977.jpg" alt="">
    <img src="https://i.pinimg.com/236x/89/26/64/892664d38ee75481cc1f47c51ce0a856.jpg" alt="">
    <img src="https://i.pinimg.com/236x/62/44/84/624484190ad581cd74e3c55f87d9139c.jpg" alt="">
    <img src="https://i.pinimg.com/236x/6b/23/57/6b2357f30dc52bcf7814d2ac66a0fb06.jpg" alt="">
    <img src="https://i.pinimg.com/236x/a6/b1/2d/a6b12d743e6d97e0f780a41b099032b5.jpg" alt="">
    <img src="https://i.pinimg.com/236x/89/0b/6e/890b6e7594b567c81ea71dc9eca88cb7.jpg" alt="">
    <img src="https://i.pinimg.com/236x/92/c1/02/92c1022570e1e610b52218f3f53eb41f.jpg" alt="">
    <img src="https://i.pinimg.com/236x/a6/4d/ef/a64defc7fd881e921df07bad0ef1131c.jpg" alt="">
    <img src="https://i.pinimg.com/474x/ed/aa/6d/edaa6d5028375176d5e35279ae9639e7.jpg" alt="">
    <img src="https://i.pinimg.com/474x/d6/ad/c8/d6adc8f67c3c160620e761de4c7bbe4c.jpg" alt="">
</div>

<style>
    .imageGrid {
        display: grid;
        grid-template-columns: repeat(5, 1fr);
        grid-gap: 1rem;
    }
    .imageGrid img {
        width: 100%;
        border: 2px solid black;
        border-radius: 10px;
        height: 300px;
        object-fit: cover;
    }
    img:hover{
        transition: all 0.3s ease;
        transform: scale(1.05);

    }
    .imageGrid img:n {
        
    }

    img:nth-child(2n+1) {
        background: lightgreen;
        margin-top:50px;
    }

    :global(body){
        background: rgb(141, 140, 140);
    }
</style>