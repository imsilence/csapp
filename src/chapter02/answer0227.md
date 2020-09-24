int uadd_ok(unsigned x, unsigned y) {
    unsigned z = x + y;
    return z >= x && z >= y;
}